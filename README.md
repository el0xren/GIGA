# GigaUserbot

Giga is a powerful telegram userbot written in Go with the help of [gotd](https://github.com/gotd/td) and [gotgproto](https://github.com/anonyindian/gotgproto).

## Progress and Deployment
The userbot is still under development but you can deploy it through your console by following a few steps:

- Create config file
    -> `cp sample_config.json config.json`
  
  After copying the sample config to build config, just fill up the required fields in config file. 
- Build the project
    -> `go build . -o giga`
- Run the binary built 
    -> `./giga`


## License
[![GNU Affero General Public License v3.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
[Licensed under GNU AGPL v3.0.](https://www.gnu.org/licenses/agpl-3.0.en.html#header)   
**Note**: Selling the codes to other people for money is *strictly prohibited*.