# DiscourseUsExtras

DiscourseUsExtras is a plugin for creating new user field type under Customize > Users > Field Types that allows to enhance the user data with Phone Number, Zip Code and/or State those inputs has custom validations which are the main goal of this plugin. 

## Installation

Follow [Install a Plugin](https://meta.discourse.org/t/install-a-plugin/19157)
how-to from the official Discourse Meta, using `git clone https://github.com/duranmla/discourse-us-extras.git`
as the plugin command.

## Usage

In order to use one of the custom inputs go to Customize > Users > Field as admin user within your discourse platform select the DiscourseUsExtras input type and add one of the following supported options:

- zip_code: Renders an input with custom validation for valid zip codes for US
- phone_number: Renders an input with custom validation for valid US phone numbers
- state: Renders a dropdown with the list of states on US so the user can select one of them

## Feedback

If you have issues or suggestions for the plugin, please bring them up on
[Discourse Meta](https://meta.discourse.org).
