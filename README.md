# Learners Guild Scripts

A `/bin` directory of handy utility scripts for the [LearnersGuild](https://github.com/LearnersGuild/) codebase.

These scripts are for common tasks associated with developing software for the LG platform, for example:

- Starting the core suite of services for local development
- Keeping all repositories up-to-date with their remotes
- General environment upkeep and maintenance

## Getting Started

Clone the repository and create a `.env` file from the example `.env.example`:

```sh
cp .env.example .env
```

Modify the variables in your `.env` file to fit your configuration needs.

### Install `pip`

https://www.rethinkdb.com/docs/install-drivers/python/

```sh
sudo pip install rethinkdb
```

## Usage

All scripts are executable files without a file extension.

Each script should be executable from any directory, but are generally assumed to be use from the parent directory of this repository, for example:

```sh
./bin/git-clone-all
```

To create a new script, start by copying the `script-template` file, which already has executable file permissions and some setup code for you to modify.

All scripts should include a comment header describing how they are intended to be used.
