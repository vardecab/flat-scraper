# flat-scraper

>Scrape apartment offers from OLX․pl, analyse them using artificial intelligence (AI) model and run IFTTT automation (eg. send email; add a to-do task) when new offer(s) matching search criteria is found. 
<!-- With support for native macOS & Windows 10 notifications.  -->

<!-- ## Screenshots -->

<!-- ![Windows](#) -->
<!-- ![macOS](#) -->

<!-- ## How to use

<!-- ## Roadmap

- lorem ipsum --> 

## Release History

- 0.5: Started to build some `if/else` logic for when offer is modern/ancient. 
- 0.4: Added v1 of AI model to assess which offer shows new ("modern") and which old ("ancient") apartments.
- 0.3: Downloading offers' main images'.
- 0.2: Getting offers' URLs + offers' main images' URLs.
- 0.1: Initial release.

## Versioning

Using [SemVer](http://semver.org/).

## License
![](https://img.shields.io/github/license/vardecab/flat-scraper)

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
<!-- - [termcolor](https://pypi.org/project/termcolor/) -->

### Stack Overflow
- [certificate issue fix](https://stackoverflow.com/questions/52805115/certificate-verify-failed-unable-to-get-local-issuer-certificate)
- [click Windows 10 notification to open URL](https://stackoverflow.com/questions/63867448/interactive-notification-windows-10-using-python)

### Other
- Images used to train the model were downloaded from Google Images. Respective licenses apply.
<!-- - [Flaticon / Freepik](https://www.flaticon.com/) -->
- [IFTTT](https://ifttt.com/) 
- [Connect a Python Script to IFTTT by Enrico Bergamini](https://medium.com/mai-piu-senza/connect-a-python-script-to-ifttt-8ee0240bb3aa)
- [Use IFTTT web requests to send email alerts by Anthony Hartup](https://anthscomputercave.com/tutorials/ifttt/using_ifttt_web_request_email.html)
- [Image classification](https://www.tensorflow.org/tutorials/images/classification)

## Contributing

![](https://img.shields.io/github/issues/vardecab/flat-scraper)

If you found a bug or want to propose a feature, feel free to visit [the Issues page](https://github.com/vardecab/flat-scraper/issues).