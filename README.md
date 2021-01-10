# Symfony console command using the library decisions a transportation problem

## Library

https://github.com/sergeiki/trpr

## Installation

composer create-project symfony/skeleton trpr-project

cd trpr-project

composer req sergeiki/trprs

#### Instead a recipe, manually copy from vendor/sergeiki/trprs/:

- src/Command/* to src/Command

- data/* to data

## Examples of using

php bin/console app:tr

php bin/console app:tr --help

php bin/console app:tr -omax data1.txt

## Checking result

There is the online decision on https://math.semestr.ru/transp/
