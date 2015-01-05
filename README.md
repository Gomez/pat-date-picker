##pat-pickadate

A Patternslib pattern which wraps the [Pickadate](http://amsul.ca/pickadate.js/) library.

##demo

To view a demo of how this pattern works, clone the repository:

    git clone https://github.com/Patternslib/pat-masonry.git

The run the Makefile:

    make

And then in your browser open: http://localhost:4001

## Documentation

Property                     | Type        | Default Value                       | Description
-----------------------------|-------------|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------
date                         | (object)    |                                     | Date widget options described here. If false is selected date picker wont be shown. ({{selectYears: true, selectMonths: true })
time                         | (object)    |                                     | Time widget options described here. If false is selected time picker wont be shown. ({})
separator                    | (string)    |                                     | Separator between date and time if both are enabled.
class-clear-name             | (string)    | 'pattern-pickadate-clear'           | Class name of element that is generated by pattern. ('pattern-pickadate-clear')
class-date-name              | (string)    | 'pattern-pickadate-date'            | Class applied to date input. ('pattern-pickadate-date')
class-date-wrapper-name      | (string)    | 'pattern-pickadate-date-wrapper'    | Class applied to extra wrapper div around date input. ('pattern-pickadate-date-wrapper')
class-separator-name         | (string)    | 'pattern-pickadate-separator'       | Class applied to separator. ('pattern-pickadate-separator')
class-time-name              | (string)    | 'pattern-pickadate-time'            | Class applied to time input. ('pattern-pickadate-time')
class-time-wrapper-name      | (string)    | 'pattern-pickadate-time-wrapper'    | Class applied to wrapper div around time input. ('pattern-pickadate-time-wrapper')
class-timezone-name          | (string)    | 'pattern-pickadate-timezone'        | Class applied to timezone input. ('pattern-pickadate-timezone')
class-timezone-wrapper-name  | (string)    | 'pattern-pickadate-timezone-wrapper'| Class applied to wrapper div around timezone input. ('pattern-pickadate-timezone-wrapper')
class-wrapper-name           | (string)    | 'pattern-pickadate-wrapper'         | Class name of element that is generated by pattern. ('pattern-pickadate-wrapper')


Camel case options are also available, to keep compatibility with [Mockup](https://github.com/plone/mockup) patterns.

Property                     | Type        | Default Value                       | Description
-----------------------------|-------------|-------------------------------------|------------------------------------------------------------------------------------------------------
classClearName               | (string)    | 'pattern-pickadate-clear'           | Class name of element that is generated by pattern. ('pattern-pickadate-clear')
classDateName                | (string)    | 'pattern-pickadate-date'            | Class applied to date input. ('pattern-pickadate-date')
classDateWrapperName         | (string)    | 'pattern-pickadate-date-wrapper'    | Class applied to extra wrapper div around date input. ('pattern-pickadate-date-wrapper')
classSeparatorName           | (string)    | 'pattern-pickadate-separator'       | Class applied to separator. ('pattern-pickadate-separator')
classTimeName                | (string)    | 'pattern-pickadate-time'            | Class applied to time input. ('pattern-pickadate-time')
classTimeWrapperName         | (string)    | 'pattern-pickadate-time-wrapper'    | Class applied to wrapper div around time input. ('pattern-pickadate-time-wrapper')
classTimezoneName            | (string)    | 'pattern-pickadate-timezone'        | Class applied to timezone input. ('pattern-pickadate-timezone')
classTimezoneWrapperName     | (string)    | 'pattern-pickadate-timezone-wrapper'| Class applied to wrapper div around timezone input. ('pattern-pickadate-timezone-wrapper')
classWrapperName             | (string)    | 'pattern-pickadate-wrapper'         | Class name of element that is generated by pattern. ('pattern-pickadate-wrapper')
