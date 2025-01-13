# LonaDB Swiss Army Knife
This is a tool to help you manage your LonaDB database. It is a command line tool that allows you to interact with your database in a variety of ways. You can use it to create, read, update, and delete records in your database. You can also use it to run queries and view the results. The tool is designed to be easy to use and flexible, so you can use it in a variety of ways to suit your needs.

## Installation
To use the LonaDB Swiss Army Knife, you need to have PHP installed on your system. You can download PHP from the [official PHP website](https://www.php.net/downloads). Once you have PHP installed.

## Usage

```bash
./swissArmyKnife [LonaDB base directory] [command] [options]
```

### Commands
- `config` set [key] [value] - Set a configuration value
- `config` get [key] - Get a configuration value
- `config` print - Print the current configuration

- `table` create [name] - Create a new table
- `table` delete [name] - Delete a table
- `table` print - Print the table

- `table` [name] set [key] [value] - Set a value in a table
- `table` [name] get [key] - Get a value from a table
- `table` [name] delete [key] - Delete a value from a table
- `table` [name] allow [user] [permission] - Allow a user to perform an action on a table
- `table` [name] deny [user] [permission] - Deny a user from performing an action on a table
- `table` [name] print - Print the table

- `user` create [name] [password] - Create a new user
- `user` delete [name] - Delete a user
- `user` allow [name] [permission] - Allow a user to perform an action
- `user` deny [name] [permission] - Deny a user from performing an action
- `user` role set [name] [role] - Set a user's role
- `user` print - Print the users

- `changeEncryptionKey` [newKey] - Change the encryption key for the configuration file

- `backup` users [file] - Backup the users to a file
- `backup` table [name] [file] - Backup a table to a file

- `restore` users [file] - Restore the users from a file
- `restore` table [name] [file] - Restore a table from a file

## License
This project is licensed under the GNU Affero General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
This project was created as part of the LonaDB project. LonaDB is a simple, lightweight, and secure database system that is designed to be easy to use and flexible. You can learn more about LonaDB on the [official website](https://lona-development.org).
