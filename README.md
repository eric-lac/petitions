# We The People petitions application

The Drupal 7 code base is used to build an application that lets users create and sign petitions.

This application is under active development and will continue to be modified and improved over time. The current release is an "alpha." (see “Roadmap” section below).

## Goals

President Obama is committed to creating the most open and participatory government in our nation’s history, and this petitioning platform is a key part of that initiative. In September 2011, the White House launched [We the People](http://petitions.whitehouse.gov), a powerful and simple way to petition the Obama Administration to take action on a range of issues. If a petition gathers a minimum number of signatures in a defined amount of time, policy officials review it and publish an official response.

*Among our commitments, we’re launching a new online tool -- called “We the People” -- to allow Americans to directly petition the White House, and we’ll share that technology so any government in the world can enable its citizens to do the same.*

-- President Barack Obama, September 20, 2011

Releasing the source code for this application is meant to empower other governments and organizations to use similar petitioning platforms to engage their own citizens and constituencies. In addition, public review and contribution to the application’s code base will help strengthen and improve the platform.

## Requirements

* Drupal 7.x
* MySQL 5.x
* PHP 5.2+

*Recommended:*

* RAM +512 M

## Usage

Site visitors can create a user account, log in, and create petitions. Petition creators can share the URL for their petition to generate signatures. When the petition crosses a certain threshold, the petition becomes "public" and is listed as an open petition on the site's "open petitions" page.

Visitors can sign petitions. Petitions that receive a designated number of signatures (at the White House the number is 100,000 in one month) get a response.

For installation instructions, see INSTALL.md.

NOTE: Setting up the application and configuring it for use in your organization’s context requires Drupal development experience. The application ships with a similar design (theme) to what is used on petitions.whitehouse.gov and needs to be customized for use by others using standard Drupal 7 theming conventions. The application also ships with various user interface elements, user account settings, and other configurations that users should expect to customize using standard Drupal 7 techniques and conventions.

## Roadmap

We the People is a work in progress and currently exists at a very basic level of functionality. Priorities for future development are detailed below.

The following descriptions are for informational purposes only and should not be interpreted as commitments or guarantees of future code releases in any way.

*Install Profile*

The codebase is released as-is and currently supports a specific, standalone website. In the future, we would like to provide an install profile that supports a wider range of applications.

*Generic Theme*

The current codebase replicates the theme used on the White House website. In the future, we would like to provide a generic, "white label" Drupal 7 theme.

*Improved Social Media Integration*

The current platform allows basic sharing of petitions, responses, and other content on the site via social media platforms like Facebook and Twitter. In the future, we would like to reduce the friction of signing a petition by making it possible to sign a petition in the context of a social network (e.g. by “liking” an object on Facebook).

## Contributing

Anyone is encouraged to contribute to the project by [forking](https://help.github.com/articles/fork-a-repo) and submitting a pull request. (If you are new to GitHub, you might start with a [basic tutorial](https://help.github.com/articles/set-up-git).)

By contributing to this project, you grant a worldwide, royalty-free, perpetual, irrevocable, non-exclusive, transferable license to all users under the terms of the [Gnu General Public License v2](http://www.gnu.org/licenses/gpl-2.0.html) or later.

All comments, messages, pull requests, and other submissions received through official White House pages including this GitHub page are subject to the Presidential Records Act and may be archived. Learn more http://WhiteHouse.gov/privacy

## License

This project constitutes a work of the United States Government and is not subject to domestic copyright protection under 17 USC § 105.

The project utilizes code licensed under the terms of the GNU General Public License and therefore is licensed under GPL v2 or later.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
