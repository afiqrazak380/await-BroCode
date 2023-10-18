// await = make async function wait for Promise

// The async function 'loadFile' sets 'fileLoaded' to false and checks 
// if it's true, returning a success message if so; otherwise, it throws an error message.
async function loadFile(){

  let fileLoaded = false;

  if(fileLoaded){
    return "The file is loaded";
  }
  else{
    throw "The file is missing";
  }
};

// The async function 'startProcess' is defined.
// 'try' block attempts to execute the code within it.
// 'await' is used to pause the execution until the promise returned by 'loadFile' is settled.
// If successful, the resolved value from 'loadFile' is stored in the 'message' variable and then logged.
// If an error occurs, it's caught in the 'catch' block, and the error message is logged.
async function startProcess(){
  try{
    let message = await loadFile();
    console.log(message);
  }
  catch(error){
    console.log(error);
  }
}

// The 'startProcess' function is called to initiate the asynchronous process.
startProcess();
