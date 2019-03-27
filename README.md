# Bash-MCLV

This is a stripped-down bash version of my Mailchimp List Viewer. When run from a terminal or command line, it will prompt the user for a valid Mailchimp API key. Once it's been given a valid key, it will show the user the names of all of the lists in the given account, along with the total number of lists, and the total number of subscribers across all lists. It's a good way to get a quick snapshot of how an account is set up.

## Getting Started

This script requires the "jq" plugin. Make sure you have it installed in your bash client if you want this to work.

### Installing

To install this, add it to your bin directory (likely located at /bin), and then make sure you change the permissions so it's executable by using "chmod u+x mclv".

## Built With

I used nothing but vi to build this, as it was just a quick script. I know there are better editors out there, but it got the job done for this project.

## Contributing

No contributing is allowed at this time.

## Authors

* **Austin Sirkin**

## License

This project is licensed under the MIT License.

## Acknowledgments

This code was entirely written by Austin Sirkin, but I'd like to thank Google and StackOverflow for answering my questions as they arose.
