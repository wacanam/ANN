<!DOCTYPE html>
<html>

<head>
  <title>Car "Miles per Gallon" (MPG) prediction : TensorFlow.js</title>
  <!-- Import Bootstrap.css -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
    integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <!-- Import TensorFlow.js -->
  <script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.0.0/dist/tf.min.js"></script>
  <!-- Import tfjs-vis -->
  <script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs-vis@1.0.2/dist/tfjs-vis.umd.min.js"></script>

  <!-- Import Bootstrap.js cdn -->
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
    integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
    crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
    integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
    crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
    integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
    crossorigin="anonymous"></script>

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <!-- Import the main script file -->
  <script src="./assets/script.js"></script>

</head>

<body>
  <div class="jumbotron">
    <h2>Car "Miles per Gallon" (MPG) prediction</h2>
      <div class="input-group-append">
        <button id="train" class="btn btn-outline-danger" type="button">Train</button>
        <button id="pred" class="btn btn-outline-success" type="button">Predict</button>
      </div>
    </div>
    <div class="m-auto">
      <p class="text-danger" id="log"></p>
      <h3 id="res"></h3>
    </div>
  </div>


  <script>
    $(document).ready(function () {
      // $("#pred").click(function(){
      //   // Load and plot the original input data that we are going to train on.
      //   const data = {mpg: 16, horsepower: 140};

      //   // Create the model
      //   const model = createModel();

      //   tfvis.show.modelSummary({
      //     name: 'Model Summary',
      //     tab: "Model Summary"
      //   }, model);
      //   // Convert the data to a form we can use for training.
      //   const tensorData = convertToTensor(data);
      //   const { inputs, labels } = tensorData;

      //   testModel(model, data, tensorData);


      // });
      $("#train").click(async function train() {

        // Load and plot the original input data that we are going to train on.
        const data = await getData();

        // Create the model
        const model = createModel();

        tfvis.show.modelSummary({
          name: 'Model Summary',
          tab: "Model Summary"
        }, model);
        // Convert the data to a form we can use for training.
        const tensorData = convertToTensor(data);
        const { inputs, labels } = tensorData;

        // Train the model  
        document.getElementById("log").innerHTML = "Training Model, Please wait!";
        await trainModel(model, inputs, labels);
        document.getElementById("log").innerHTML = "Done Training";
        console.log('Done Training');

      });
    });
  </script>


</body>

</html>