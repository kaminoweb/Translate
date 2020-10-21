## Description

This bash script is using AWS CLI to translate various languages with "AWS Translate".

## Requirements

1. Linux operating system.
2. AWS account. If you don't have one, sign up for AWS.  
<https://docs.aws.amazon.com/translate/latest/dg/setting-up.html#setting-up-signup>

3. IAM user. If you don't have one, create an IAM user.  
<https://docs.aws.amazon.com/translate/latest/dg/setting-up.html#setting-up-iam>

4. Set Up the AWS Command Line Interface (AWS CLI).  
<https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-linux.html>

5. dig must be installed. It is used to check if we have internet access before to communicate with AWS. 

## Installation

To install this script and get it working, follow the steps below:

1. Download the script 
```
wget https://raw.githubusercontent.com/kaminoweb/Translate/master/Translate.bsh
chmod 700 Translate.bsh
```
2. Run the script
```
./Translate.bsh
```

## Supported Languages

At this time, the script handles only the following languages:

  fr - French
  en - English
  es - Spanish
  it - Italian
  pl - Polish

AWS Translate supports more languages.  
<https://docs.aws.amazon.com/translate/latest/dg/what-is.html>

# License

This WordPress plugin is licensed under the GPL v2 or later.

> This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License, version 2, as published by the Free Software Foundation.

> This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

> You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA

A copy of the license is included in the root of the plugin’s directory. The file is named `LICENSE`.


