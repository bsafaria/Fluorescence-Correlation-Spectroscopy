
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

Fluorescence Correlation Spectroscopy (FCS) is an analytical technique that monitors the movement of fluorescent particles within a solution. It starts with selecting fluorophores (glow-capable particles) that absorb a specific wavelength emitted by a laser, or conversely, choosing a laser that matches the absorption characteristics of the fluorophores being studied. Once the setup is ready, the fluorescent particles diffuse through the solution, occasionally entering the area illuminated by the focused laser beam. When they do, they absorb the laser light and re-emit it at a longer wavelength, a process known as fluorescence. This emitted light varies in intensity over time, directly correlating to the number of fluorescent particles present in the laser-illuminated area. Despite the laser illuminating a relatively large volume of the sample, FCS technology concentrates on a much smaller region. This is achieved by tightly focusing the laser beam and configuring the instrument's optics to detect light only from the focal volume around the beam's most concentrated point. Through this approach, FCS provides detailed insights into the dynamics and concentration of these particles within a confined space.

In FCS, a tiny volume in a solution is defined using a tightly focused laser beam and by capturing fluorescence solely from this focused area. This is achieved with a high-numerical-aperture objective lens for laser focusing and a spatial filter (pinhole) in the detection optics to select light from the correct focal plane. The lens's focusing power, determined by the numerical aperture (NA), depends on the refractive index of the medium (air, water, or oil) and the angle of incoming light. However, due to light's wave nature, the smallest focus achievable is about half the wavelength of light, setting the lower limit on the focal volume size. By placing a spatial filter in the light path, FCS accurately detects photons from a specific volume, crucial for precise measurements. This technique is extensively used in biophysics for studying minute-scale phenomena like protein interactions, cellular processes, and biomolecular changes.

With a high concentration of fluorophores in a solution, the fluorescence signal detected is strong and stable over time. As the concentration decreases, there's a noticeable reduction in the average fluorescence intensity, accompanied by greater fluctuations around this average. In an extremely diluted sample, the photomultiplier tube (PMT) typically registers no signal due to the absence of fluorophores in the focal volume. When a fluorophore does enter this volume, it is excited by the laser and emits a burst of fluorescence, with the duration of this burst reflecting the time the fluorophore spends in the focal area. The frequency of these bursts gives insights into the concentration of fluorophores in the solution. For accurate determination of diffusion properties and concentration, it's more effective to operate in a regime where these bursts slightly overlap, maximizing signal variation. The autocorrelation function of the intensity is utilized as a mathematical tool to deduce this information, which is key in understanding molecular behaviours such as binding, aggregation, and changes in structure.

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
