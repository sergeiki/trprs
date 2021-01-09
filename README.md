# Symfony console command using the library decisions a transportation problem

## Features

- Validating for a closed task
- First Base plan is calculated by Northwest corner method
- Checking the Base plan on degeneracy  
- Improvement method of Base plan is the Potentials method
- Optimality criterion: min or max [default: "min"]
- The input data from a csv-file with a tab delimiter making by manually copy table from Excel to it

## Installation

composer create-project symfony/skeleton trpr-project

cd trpr-project

composer req sergeiki/trprs

### Instead a recipe manually copy from vendor/sergeiki/trprs

src/Command/* to src/Command

data/* to data

## Using

php bin/console app:tr

php bin/console app:tr --help

php bin/console app:tr -omax data1.txt

## Checking

There is the online decision on https://math.semestr.ru/transp/
