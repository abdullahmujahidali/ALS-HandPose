<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<!-- <p align="center">
  <a href="https://www.jala.tech">
    <img alt="Tambak Pintar Jala" src="https://jala.tech/wp-content/uploads/2020/11/Logo-Tambak-Pintar-07-e1604579893539.png" width="200" />
  </a>
</p> -->
<h1 align="center">
  HandPose ~ American Sign Language
</h1>

Handsign is a simple AI-based hand gesture recognition that translates a hand pose into the American Sign Language (ASL) alphabet. Using Tensorflow JS and its Handpose preloaded model to detect the hand object and its parts. Handsign also uses an additional library called Fingerpose to classify certain of custom hand gestures based on the finger position.

`#dohackathon` `#madewithTFJS`



# Installation
1. **Clone the repository**

  ```shell
  # copy the repo to your machine

  git clone https://github.com/abdullahmujahidali/ALS-HandPose
  ```

2. **Start the project**

  ```shell
  # move to the project folder and install all dependencies
  
  cd handsign-tensorflow-gatsby
  yarn install
  ```

3. **Run the project on your local machine**

  ```shell
  # run Gatsby

  yarn develop
  ```

4. **The project is live 🚀**
  
  Your project is live and running at `http://localhost:8000`

  You can edit the core program at `src/pages/app.js`

# What's inside the project
## Extract the fingerpose data

uncomment the `<pre>` component

  ```js
  <Image h="150px" objectFit="cover" id='emojimage'/> 

  // uncomment this
  {/* <pre className="pose-data" color="white" style={{position: 'fixed', top: '150px', left: '10px'}} >Pose data</pre> */}

  </Container>
  ```
uncomment the `estimatedGestures` data to change `'.pose-data'` innerHTML

  ```js
  // document.querySelector('.pose-data').innerHTML =JSON.stringify(estimatedGestures.poseData, null, 2);
  ```
the `estimatedGestures` data will render on your screen.

# References & Libraries
* [Tensorflow JS](https://www.tensorflow.org/js) - A Library for ML in JS.

* [Handpose](https://github.com/tensorflow/tfjs-models/tree/master/handpose) - A lightweight ML pipeline consisting of two models: A palm detector and a hand-skeleton finger tracking model.

* [Fingerpose](https://github.com/andypotato/fingerpose) - A pose classifier for hand landmarks detected by TensorFlow.js Handpose's model.

<!-- AUTO-GENERATED-CONTENT:END -->
# ALS-HandPose
