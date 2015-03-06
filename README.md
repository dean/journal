## Installation

Clone the repository and move the file to /usr/bin to keep it on your path.

```sh
git clone https://github.com/dean/journal.git
cd journal
sudo cp journal /usr/bin
```

## Configuration

By default, a folder called .journal is created in the user's home folder that
runs the application. Inside that folder there are two folders:
```
    templates - This holds the templates you want to apply to new journals.
    entries - This holds all journal entries you make
```
Additionally, you can create an order.txt file in ~/.journal/ to specify the
order in which to organize your templates in a journal entry.

An example of these is included in the /examples directory.


## Support

Please [open an issue](https://github.com/dean/journal) for questions and concerns.

## Contributing

Fork the project, commit your changes, and [open a pull request](https://github.com/dean/journal/compare/).
