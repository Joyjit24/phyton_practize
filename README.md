# phyton_practize
Practising Phyton
name: phyton application

on: [push]

jobs:
 build:

   runs-on: ubentu-latest

   steps:
  - name: check out the code
    uses: actions/checkout@v2
