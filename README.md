# Odoo Module Builder

Forget to make the odoo module from scratch, let's just make it with the csv file
Made to facilitate and shorten time, testing with python version 2.7.x

  - Create Manifest
  - Create Model
  - Create View

### How To Use

I tried it with version 2.7.x python. Ff you get trouble, feel free to contact me
Okey lets begin...

Clone this Repo
```sh
$ clone https://github.com/andrepurnomo/odoo-module-builder
$ cd odoo-module-builder
```

Run Python File...

```sh
$ python builder.py
$ Insert Module Name : ... #insert your module name (example : Rental Mobil)
$ Insert Path to CSV : ... #insert your path location to csv (example : rental.csv)
$ Insert Path to Save : ... #insert your path location for result (exanoke : carent)
```

### File CSV

Following the data needed in the csv file, give the TRUE sign to true or leave it blank for FALSE

| Key | Description |
| ------ | ------ |
| model | Model Name |
| field | Field Name |
| type | Field Type |
| comodel_name | Comodel Name |
| inverse_name | Inverse Name |
| string | String of Field |
| help | Help popup for Field |
| readonly | True for Readonly Field |
| required | True for Required Field |
| index | Index of Field |
| default | Default value for Field |
| states | State for Field |
| groups | Grouping Field |
| copy | True for enable duplicate |
| domain | Domain for Field |
| tree | True for enable field in tree view |
| form | True for enable field in form view |
| selection | fill only when type field is selection |


### Contact

Feel free to contact me
Email:
```sh
andrepurnomo04@gmail.com
```
