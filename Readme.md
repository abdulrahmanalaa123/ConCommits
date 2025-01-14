# Requirements (Or rough flow of the script its basically simple) 
- installing needs to create an alias for the commit
- needs to run from the current directory
- needs to detect context if its current or there exists a parent directory
- need to save the config status in a specific format
- adding either prompts for the files when none is provided it targets all
- prompt for each of the messages from the messages shape provided

# Functionalities

take in configurations as options and create a man doc i presume

## Functions: 
- add
- commit
- find current git repos
- initialize remote local
- initialize commit file in a well documented format which has the default configs for deafult adding

options to deny any would negate the default and would prompt or if not found just prompts it
configurations:
- - `default scope`
- - `linebreak`
- - `prompt body`
- - `prompt footer`
- - `default add`
- - `default remote`
- - `prompt scope`
- - `default repo either (current or parent for example)`

[Messages shape](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

[HomePage for reference](https://www.conventionalcommits.org/en/v1.0.0/#summary)
