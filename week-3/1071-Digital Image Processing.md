# Digital Image Processing

### What is Digital Image Processing?

* **Digital Image:** A representation of a two-dimensional image as a finite set of digital values, called picture elements or pixels. _f(x, y)_
* Where x, y are spatial coordinates&#x20;
  * **f(x, y) = i(x,y) \* r(x,y)**
  * f(x, y): Intensity at given point (x, y)
  * i(x, y): Illumination at (x, y)
  * r(x, y): Reflectance/ Transmissivity at (x, y)

M X N representation of _f_

### Image Acquisition Process

![](<../.gitbook/assets/image (30).png>)

### Pixel & Digitization

* Pixels are the elements of a digital image that typically represent gray levels, colours, heights, opacities.
* Digitization implies that a digital image is an approximation of a real scene in the numerical matrices form

![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FwPC5pgXmNYyWxYfcOHvZ%2Fimage.png?alt=media&token=c6dab5b2-fd35-4e40-82b1-b49babc175f9)

### Digital Image

Common digital image formats include

* 1 sample per point (B\&W / Grayscale)
* 3 samples per point ( Red, Green and Blue)
* 4 samples per point (Red, Green, Blue and Alpha / opacity)

![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FxUT9YZl6rPtz9OrrkOcX%2Fimage.png?alt=media&token=2ad0e5cb-3abb-497b-9c04-4e7d9dcc6583)

### What is Digital Image Processing?

* **Digital Image Processing:** Processing digital images by means of a computer.
* An **image processing** operation typically defines a new image _g_ in terms of an existing image _f._
* We can transform either the range of _f_.

![formula](https://raw.githubusercontent.com/dphi-official/five-week-deep-learning-bootcamp/master/.gitbook/assets/image%20(19).png)



* Or the domain of _f_:

![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2F9M4cQ4m8RAOxMWAYbxrA%2Fimage.png?alt=media&token=e33b4de5-531d-4902-a7ba-34c64d32f658)

### Why Digital Image Processing?

* Improvement of pictorial information for human interpretation
* Processing of image data for storage, transmission and representation for autonomous machine perception
* Where image processing ends, fields such as image analysis and computer vision start.
* The continuum from image processing to computer vision is broken down into:
  * Low – Level:
    * Inputs and outputs are images
    * Ex: Noise Removal, Image Sharpening
  * Mid – Level:
    * Outputs are the attributes extracted from input images&#x20;
    * Ex: Object Recognition, Image Segmentation
  * High – Level:
    * An ensemble of recognition of individual objects&#x20;
    * Ex: Scene Understanding, Autonomous Navigation

For more details about each of the steps in the next set of slides refer this article: [https://medium.com/futframe-ai/fundamental-steps-of-digital-image-processing-d7518](https://medium.com/futframe-ai/fundamental-steps-of-digital-image-processing-d7518d6bb23c) [d6bb23c](https://medium.com/futframe-ai/fundamental-steps-of-digital-image-processing-d7518d6bb23c)

### Key Stages in Digital Image Processing

![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FkDNnaGKE9lfqt9QISCHB%2FScreen%20Shot%202022-03-30%20at%205.12.30%20PM.png?alt=media&token=62d35ca6-e381-4b05-ad96-45c7b22a3d91)

![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FZ12fqvCgsnyceLbnKYyq%2FScreen%20Shot%202022-03-30%20at%205.14.38%20PM.png?alt=media&token=c4e77603-4bb8-4522-9a95-2269a9e15ea4) ![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FE6csjoUMpYtHKm2mnxej%2FScreen%20Shot%202022-03-30%20at%205.15.10%20PM.png?alt=media&token=322a1767-d295-4596-9106-49ebe7842b40) ![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FBrw5j9Uxhq2MfLoGy3it%2FScreen%20Shot%202022-03-30%20at%205.15.20%20PM.png?alt=media&token=ce14323f-bb4b-41e1-8229-d166d2374da1) ![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FuqfPN5jzjRVBb8grWPLn%2FScreen%20Shot%202022-03-30%20at%205.15.29%20PM.png?alt=media&token=7375d234-0813-4df2-821b-1ebd5c97fc12) ![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FyUr4rDoTFI6js6ajwoqa%2FScreen%20Shot%202022-03-30%20at%205.15.37%20PM.png?alt=media&token=74cfdfe2-072e-47ad-ba20-eaaa9f0391db) ![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2Fex7TpCbIPjkmcWLRRH3D%2FScreen%20Shot%202022-03-30%20at%205.15.45%20PM.png?alt=media&token=3af38a6f-9ccd-4431-af2f-a90cf5c59281) ![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FOdwhD8xn9ty5BTUSHxSL%2FScreen%20Shot%202022-03-30%20at%205.15.55%20PM.png?alt=media&token=6cf7c70b-4d75-4b25-9104-b7316b35e4eb)
![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FzaafCuuNo7FgvkU6ax53%2FScreen%20Shot%202022-03-30%20at%205.16.07%20PM.png?alt=media&token=c46056eb-18b2-492a-aad1-d8551c7edfca)
![](https://3298224505-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FO6zK5zzcnrnToWx3Brks%2Fuploads%2FLYDnAFWMrQb2f4RJ62zo%2FScreen%20Shot%202022-03-30%20at%205.16.18%20PM.png?alt=media&token=3394b632-b193-4e42-834d-bf02beb664f0)

### Applications

* Document Handling&#x20;
* Signature Verification&#x20;
* Biometric Verification&#x20;
* Object Recognition Research&#x20;
* Target Recognition&#x20;
* Interpretation of aerial photography&#x20;
* Autonomous Vehicle&#x20;
* Traffic Monitoring&#x20;
* Face Recognition and Tracking&#x20;
* Medical Applications -> Tumor detection&#x20;
* Image generations&#x20;
* Image styling