# Ruby Quick Start
We need to install RubyInstaller, RubyGems, and Rails as follow installation guide. After that, we can start the setup guide next step.

## Technology Stack
* Ruby, RubyGems, Rails
* Windows 10

## Installation Guide on Windows 10

* RubyInstaller Installation
    * Download RubyInstaller latest version from https://rubyinstaller.org/downloads/
    * Here is https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.6.5-1/rubyinstaller-devkit-2.6.5-1-x64.exe
    * Rub the installer file and choosing item 3 - MSYS2 and MINGGW development toolchain
    * Waiting untill installation processing completely 
    * Check version using command C:\ruby -v
        * It should display like >> ruby 2.6.5p114 (2019-10-01 revision 67812) [x64-mingw32]

* RubyGems Installation        
    * download zip file from https://rubygems.org/rubygems/rubygems-2.6.12.zip
    * unzip file to temporary folder
    * Open command windows and run command follow
        * cd to C:\..\Downloads\rubygems-2.6.12>
        * ruby setup.rb
        * gem -v
            * It should display like >> 2.6.12
    * It will extract all files to new folder for example C:\Ruby26-x64 automatically

* Rails Installation
    * Open command windows and run command follow
        * gem install rails --no-document
        * rails -v
            * It should display like >> Rails 6.0.0

## Setup Guide
* Open PowerShell windows and run command follow
    * git clone git@github.com:Khachornchit/Ruby-Quick-Start.git
    * cd Ruby-Quick-Start
    * ruby basic.rb
        * It will display as follow 
        ```
        Hello World
        1, John, Wisdom Apartments, Ludhiya
        2, Poul, New Empire road, Khandala
        ```
