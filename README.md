
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#resources">Resources</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Product Name Screen Shot][product-screenshot]

Fluorescence Correlation Spectroscopy (FCS) tracks fluorescent particles in a solution, starting with selecting particles that absorb laser light and emit it at a longer wavelength. This fluorescence varies in intensity, reflecting the number of particles in the laser's focus. Although the laser covers a larger area, FCS zeroes in on a smaller region by tightly focusing the laser and using specific optics to detect light only from this focal area, offering precise insights into particle dynamics and concentration.

In FCS, defining a small solution volume involves a focused laser beam and capturing fluorescence from this area. Achieved with a high-numerical-aperture lens and a spatial filter in the optics, the technique zeroes in on a precise focal point, although light's wave nature limits the smallest focus size. This setup is key for detecting specific photons, making FCS valuable for studying detailed biological phenomena like protein interactions and cellular processes.

The behaviour of fluorescence in FCS varies with fluorophore concentration. High concentrations yield stable, strong signals, while lower concentrations show reduced intensity and increased fluctuations. In very diluted samples, bursts of fluorescence occur when fluorophores enter the focal area, with burst frequency indicating concentration. To accurately measure diffusion and concentration, FCS uses a regime where bursts slightly overlap, analyzed using an autocorrelation function. This analysis is crucial for understanding molecular behaviours such as binding and structural changes.

The primary objectives of the experiment were to:

1. Use the signal detected from FCS of standard-sized particles to determine the extent of the
focal volume of a laser beam.

2. Determine the expected FCS signal for particles of different sizes.

3. Construct autocorrelation functions to determine the diffusion constant and concentration of chosen particles.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

[<img src="https://scipy.org/images/logo.svg" alt="Scipy.svg" width="300" height="100">][Scipy-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Behzad Safarian Kashani - [LinkedIn](https://www.linkedin.com/in/bsk00/) - bsafariak@gmail.com

Project Link: [https://github.com/bsafaria/Fluorescence-Correlation-Spectroscopy-](https://github.com/bsafaria/Fluorescence-Correlation-Spectroscopy)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments


## Resources

* [Comprehensive FCS review](https://www.frontiersin.org/articles/10.3389/fphy.2021.644450/full)
* [Autocorrelation](https://www.sciencedirect.com/topics/mathematics/autocorrelation-function)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: https://github.com/bsafaria/Fluorescence-Correlation-Spectroscopy/blob/main/Laser%20Setup.jpg?raw=true
[Scipy.svg]: https://scipy.org/images/logo.svg
[Scipy-url]: https://scipy.org/
