# AuditoryBraille

### Inspiration
One of our team members visited a school for blind and observed the challenges of learning and using Braille in daily life. To ensure greater accessibility for the blind and visually impaired community, we decided to use our interest of computational mathematics to build AuditoryBraille - an auditory assistant to hear colors.

### What it does
AuditoryBraille is an educational tool to improve learning abilities for the blind and visually impaired so that they can use different ranges of frequencies emitted by a spectrum of colors for various applications in their daily life, such as navigating or searching a particular object and avoiding life threatening situations. Each frequency corresponds to a particular color - in general, low frequencies represent lighter colors while the darker colors are represented by higher frequencies.

### How we built it
We created a working model of AuditoryBraille that serves as a proof of concept. It works by using Inverse Fast Fourier Transformation (IFFT) to compute frequency wave forms obtained by reconstructing colored image pixels to produce audio signals. We used java, image processing, relational graphs and various APIs (sound and image) on eclipse IDE.

### Challenges we ran into
One of the challenges we faced was that we would never get the perfect result for all images that we tried to compute (which is the case for any image processing technique).

### Accomplishments that we're proud of
Implementing the IFFT algorithm was a huge accomplishment for us, along with integrating all the different components of the project such as frequency-color matching, computing each pixel value and the relational graph.

### What we learned
We conceptualized how IFFT in a mathematical theoretical model works, and then implemented that algorithm to our project using complex number theory. Furthermore, we learnt how to use the sound and image API along with displaying their corresponding graphs.

### What's next for AuditoryBraille
The vision for AuditoryBraille is to reach out to the blind community and help them to understand colors with sounds and frequencies. In order to achieve this, we plan to use a special type of equipment to scan the surroundings and play the corresponding frequencies. This whole technique can be used in schools for the blind to help educate them about the benefits of visualizing neighboring areas using colors.
