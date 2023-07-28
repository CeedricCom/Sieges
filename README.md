# Sieges

![Banner](https://github.com/CeedricCom/Earth/blob/master/branding/Banner.png?raw=true)

This repository is the server setup for ceedric's <a href="https://github.com/CeedricCom/SiegeGame">SiegeGame</a>. Here you will find previously used maps, plugins, and configurations used on `ceedric.com`. This repository along with SiegeGame simulate Goosius' <a href="https://github.com/TownyAdvanced/SiegeWar">SiegeWar</a> into a fast-paced minigame. If you are just looking for the SiegeGame plugin, visit <a href="https://github.com/CeedricCom/SiegeGame">here</a>.

# Installation

Clone this repository into the folder Sieges

Unless you connect the server to a bungeecord network it may not work as expected. To fix this you will need to edit the `spigot.yml` and change `settings.bungeecord` to false. If you want to host this on an actual server you may need to create firewall rules to open certain ports.

The following plugins are connected to external databases. In order to get them to work correctly you will either need to change their config to stop using an external database or to set up your own MariaDB database.
  - LuckPerms
  - CoreProtect

The following plugins are missing from this repository as they are paid, but their configs can still be found:
  - KnockbackMaster
  - Matrix AntiCheat
  - PremiumVanish

Connect to the server on localhost:25567

To install new maps and customise configuration (such as shop and respawn timers), follow the tutorial available in the readme <a href="https://github.com/CeedricCom/SiegeGame">here</a>.

## Related Repositories

The following repositories are linked to the project and contain other important plugins
- https://github.com/DeltaOrion/GladiaWebsite - The repository for SiegeGame's source code
- https://github.com/CeedricCom/GladiaClonePlugins - Any custom plugins used for the server

## Contributing

Pull Requests

If you make any changes or improvements to the plugin which you think would be beneficial to others, please consider making a pull request to merge your changes back into the upstream project. (especially if your changes are bug fixes!)
