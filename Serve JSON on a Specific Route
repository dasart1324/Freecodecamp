var express = require('express');
var app = express();
console.log("Hello World");
app.get("/", function(req, res) {
  res.sendFile(__dirname + "/views/index.html");
});
app.use("/public", express.static(__dirname + "/public"));
app.get("/json", (req, res) => {
  res.json({"message": process.env.MESSAGE_STYLE == "uppercase" ? "HELLO JSON" : "Hello json"})
});










































 module.exports = app;
