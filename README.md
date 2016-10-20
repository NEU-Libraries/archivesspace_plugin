# archivesspace_plugin
a plugin for archivesspace that customizes the front end for archives

Install instructions
1. download this repo to your archivesspace/plugins directory
  ```
  cd archivesspace/plugins
  git clone https://github.com/NEU-Libraries/archivesspace_plugin.git nu_archives
  ```
2. add the plugin to your config file
  ```
  cd archivesspace/config
  vi config.rb
  ```
  find the `AppConfig[:plugins]` line and add the plugin `nu_archives`
  ie. `AppConfig[:plugins] = [nu_archives]`
