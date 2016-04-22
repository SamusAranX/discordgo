<img align="right" src="http://bwmarrin.github.io/discordgo/img/discordgo.png">
Basic API Example
====

This example demonstrates how to utilize DiscordGo to connect to Discord 
and print out all received chat messages.  

This example uses the low-level REST API functions to connect to Discord.

### Build

This assumes you already have a working Go environment setup and that 
DiscordGo is correctly installed on your system.

```sh
go build
```

### Usage

You must authenticate using either an Authentication Token or both Email and 
Password for an account.  Keep in mind official Bot accounts only support
authenticating via Token.

```
./api_basic --help
Usage of ./api_basic:
  -e string
        Account Email
  -p string
        Account Password
  -t string
        Account Token
```

The below example shows how to start the bot using an Email and Password for
authentication.

```sh
./api_basic -e EmailHere -p PasswordHere
```