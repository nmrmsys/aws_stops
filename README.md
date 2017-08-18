aws_stops - AWS EC2/RDS Instance Stop/Start Tool
====

## Usage
 aws_stops --profile &lt;prof&gt; [--dry-run]

    > # Setting Stop/Start Instance Tag 
    > # Stop: 22:00, Start: 08:00 
    > aws_stops --profile prof1 

First time running recommended to add --dry-run option.<br>In actual operation, use cron

## Requirement
- aws-cli version 1.6.x or later, RDS stop/start feature supports the corresponding version
- jq 

## Licence

[MIT](http://opensource.org/licenses/mit-license.php)

## Author

[nmrmsys](https://github.com/nmrmsys)
