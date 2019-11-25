![Logo](http://supanadit.com/wp-content/uploads/2019/11/Dev-Ops-Factory.png)
# DevOps Factory
Cross Platform Swiss Army Knife for DevOps

### Changelog
#### Version 0.0.6 Alpha
- Github integration by token `devops-factory --gt <your_github_token>`
- Get all own repository from Github `devops-factory --gl`
- Get all forked repository from Github `devops-factory --glf`
- Delete all forked repository from Github `devops-factory --glfd`

#### Version 0.0.5 Alpha
- Support SSH Authentication for Git Repository
- Support Update Repository
- Remove Git Model
- Fix output without line break problem

#### Version 0.0.4 Alpha
- Support Remove Project `devops-factory --pr <project_alias>`
- Support Get List Project `devops-factory --pl`
- Support Get List SSH Project `devops-factory --kl`
- Fix Bug when Remove Keyring SSH `devops-factory --kr root@123.123.123.123`
- Support Create new Project from existing repository `devops-factory --pe /<your_project_directory>`

#### Version 0.0.3 Alpha
- Support Save SSH with Port `devops-factory --kn root@123.123.123.123:22` or it will asking the port if not include when insert host
- Instant SSH Authentication by `devops-factory --kc root@123.123.123.123`

#### Version 0.0.2 Alpha
- Support Save SSH with Keyring by `devops-factory --kn 123.123.123.123` or `devops-factory --kn root@123.123.123.123`
- Support Delete SSH with Keyring by `devops-factory --kr root@123.123.123.123`
- New Project Command change to `devops-factory --pn "Your Project Name"`

#### Version 0.0.1 Alpha
- Basic Command `devops-factory`
- Support Argument `-h` for Help
- Experimental Argument with `-n` for New Project
- Default and Basic Configuration Support
- TOML Support for any Configuration
- Auto Create Folder `DevOpsFactory` in Home Folder

### Todo
- Docker Integration
- Kubernetes Integration
- Support Continues Integration
- FTP and SFTP Integration
- Custom Script Support
- Run Script Only on Remote Server
- Deploy Repository and Run Script
- Deploy Repository using Standard Method (PHP, Python, Static HTML, etc)
- Build Server Version of DevOps Factory
- Deploy to Multi Server
- Build Multi Release App (Flutter, Angular, Java, etc)
- Support Auto Backup
- Versioning Repository
- Backup All Repository
- Environment Support
- Web GUI for `devops-factory --serve`
- Manage package for NodeJS, PHP, Flutter, Python, etc.
- Check version of each package
- Support Deploy by running `devops-factory -p test-project -t 123.123.123.123 -d "/var/www/test"`
- Support Instant Deploy by running `devops-factory -i github-project`
- Support SQL Database Backup, eg. Postgre SQL, MySQL, etc
- Support Non SQL Database backup eg. MongoDB, Pouch DB, Rethink DB, etc
- Support Tag a Directory
- Support Connect to SSH by Alias
- Update forked repository from Github
- Delete forked repository with Whitelist and Blacklist Support
- Maximum value for deleting repository is between 84 and 184, and it be must requested each 84 and 184 repositories if, the forked repository more than 84 and 184

### Support Me
[![https://patreon.com/supanadit](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](http://patreon.com/supanadit)
