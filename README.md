# flat-finder

![Not Maintained](https://img.shields.io/badge/Maintenance%20Level-Not%20Maintained-yellow.svg)

<b>As of late 2022, serious rewrite from BeautifulSoup to [Selenium](https://www.selenium.dev) is needed because BeautifulSoup is struggling to download the whole page. This results in just 5-10% images downloaded.</b>

<br>
<hr>
<br>
<br>

![](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-blue)

>Looking for a modern, nicely looking apartment but tired with all these old flats from the '90s? Let's automate that :) <br><br> Scrape apartment offers from OLX․pl, analyse them using artificial intelligence (AI) model to get only good looking flats and (optionally) run IFTTT automation (eg. send email; add a to-do task) when new offers matching search criteria (eg. ≥ 2 rooms, ≤ 2k PLN, ≥ 30m²) are found. <br><br> With support for native macOS & Windows 10 notifications. 

## Screenshots

![macOS](https://user-images.githubusercontent.com/6877391/116890697-2e49e580-ac2e-11eb-968d-7146fd10e871.png)
![Windows](https://user-images.githubusercontent.com/6877391/116942708-65da8100-ac72-11eb-8023-6e4ae0161cc2.png)

## Features

- Get offers from OLX․pl
- Pagination support
- Artificial intelligence (AI) model to assess if an aparment is modern or not
- IFTTT (eg. send an email or add a to-do task if new offer is found)
- Cross platform (macOS & Windows)
- Native notifications (macOS & Windows)

## How to use

Coming soon™.

<!-- ## Roadmap -->

<!-- - lorem ipsum  -->

## Release History

- 0.14.2: Fixed offer counter & Windows 10 notification icon not showing up. 
- 0.14.1: Added two additional calculations to know how much time it takes to train the model and how much time it takes to download and classify the images.
- 0.14: Refactored code; moved some more code to functions; added support for more than one URL with offers (eg. useful w/ multiple locations); tried to achieve feature parity between Windows and macOS; improved model accuracy; changed comparison mode so that previously seen offers are not shown again; cleaner output / general look & feel; removed unused code; other small improvements. 
- 0.13: Open folders for manual review of the images.
- 0.12: Added `colorama` to have colored output; changed URL; added more images to model's dataset; added fix for `feedModel.py` crashing due to duplicates found in target location.
- 0.11.3: Forced to look only on 3 subpages.
- 0.11.2: Increased # of epochs to improve model's accuracy; added more images to model's dataset.
- 0.11.1: Changed title in notifications.
- 0.11: Automated runs using Task Scheduler (Windows) & Automator (macOS). Added more images to model's dataset. Disabled IFTTT automation for testing.
- 0.10.2: Cleaned up the code. Added comments.
- 0.10.1: Cleaned up the code.
- 0.10: Added macOS compatibility. Enabled IFTTT automation. Improved model accuracy - newly downloaded images are used to feed the model so it can improve itself over time.
- 0.9: Pagination support.
- 0.8: Enabled Windows 10 & macOS notifications when new offers are found.
- 0.7: Downloading images to unique folders. Added data comparison logic to show which offers are new vs previous script run.
- 0.6: Adding only "modern" offers to a text file. Changed local images renaming logic.
- 0.5: Started to build some `if/else` logic for when offer is modern/ancient. 
- 0.4: Added v1 of AI model to assess which offer shows new ("modern") and which old ("ancient") apartments.
- 0.3: Downloading offers' main images'.
- 0.2: Getting offers' URLs + offers' main images' URLs.
- 0.1: Initial release.

## Versioning

Using [SemVer](http://semver.org/).

## License
![](https://img.shields.io/github/license/vardecab/flat-finder)

<!-- GNU General Public License v3.0 -->
<!-- GNU General Public License v3.0, see [LICENSE.md](https://github.com/vardecab/PROJECT/blob/master/LICENSE). -->

## Acknowledgements

### Libs
- [TensorFlow](https://github.com/tensorflow/tensorflow)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- [alive-progress](https://github.com/rsalmei/alive-progress)
- [win10toast](https://github.com/jithurjacob/Windows-10-Toast-Notifications)
- [win10toast-persist](https://github.com/tnthieding/Windows-10-Toast-Notifications)
- [win10toast-click](https://github.com/vardecab/win10toast-click)
- [pync](https://github.com/SeTeM/pync)
- [GD Shortener](https://github.com/torre76/gd_shortener) 
- [wget](https://pypi.org/project/wget/)
- [Pillow](https://python-pillow.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [colorama](https://github.com/tartley/colorama)

### Stack Overflow
- [certificate issue fix](https://stackoverflow.com/questions/52805115/certificate-verify-failed-unable-to-get-local-issuer-certificate)
- [click Windows 10 notification to open URL](https://stackoverflow.com/questions/63867448/interactive-notification-windows-10-using-python)

### Other
- Images used to train the model were downloaded from Google Images. Respective licenses apply.
- [Flaticon / Freepik](https://www.flaticon.com/)
- [IFTTT](https://ifttt.com/) 
- [Connect a Python Script to IFTTT by Enrico Bergamini](https://medium.com/mai-piu-senza/connect-a-python-script-to-ifttt-8ee0240bb3aa)
- [Use IFTTT web requests to send email alerts by Anthony Hartup](https://anthscomputercave.com/tutorials/ifttt/using_ifttt_web_request_email.html)
- [Image classification](https://www.tensorflow.org/tutorials/images/classification)

## Contributing

![](https://img.shields.io/github/issues/vardecab/flat-finder)

If you found a bug or want to propose a feature, feel free to visit [the Issues page](https://github.com/vardecab/flat-finder/issues).