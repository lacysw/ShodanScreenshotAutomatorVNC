# ShodanScreenshotAutomatorVNC

Automatically grabs screenshots from open VNC servers discovered on Shodan. Images are saved in JPEG format with names following the pattern `$IP-$Port.jpg`.

![Example Results](exampleResultsRedacted.png)

**Note:** this script exists to improve the accessibility of Shodan's existing screenshot viewer. I take no liability for any actions performed related to the use of the code in this repository.

## Preliminary setup

### Register on Shodan

 - Navigate to [shodan.io](https://account.shodan.io/register) and create an account
 - Go to [the Account page](https://account.shodan.io) and make note of your API key

### Install Dependencies

 - Shodan CLI: `$ pip install -U --user shodan`
 - vncsnapshot: `$ sudo apt install vncsnapshot`, `$ git clone https://github.com/shamun/vncsnapshot`, or your preferred way of acquiring the software

### Initialize Shodan

`$ shodan init <YOUR API KEY HERE>`

## Execution

Simply run the script -- no further configuration required.
