<template>
  <div>
    <div id="sidebar">
      <div id="email">
        <h3>Emails</h3>
      </div>
      <div class="feed">
        <button class="feedbtn" type="button">Feedback</button>
      </div>
    </div>
    <div id="routes">
      <div style="" class="name">
        <h4>Name</h4>
      </div>
      <div class="namebox">
        <h4><i class="fa fa-inbox fa-lg" aria-hidden="true"></i>Inbox</h4>
      </div>
      <div class="namebox">
        <h4><i class="fa fa-flag fa-lg" aria-hidden="true"></i>Flagged</h4>
      </div>
      <div class="namebox">
        <h4><i class="fa fa-folder-open fa-lg" aria-hidden="true"></i>Draft</h4>
      </div>
      <div class="namebox">
        <h4><i class="fa fa-paper-plane fa-lg" aria-hidden="true"></i>Sent</h4>
      </div>
      <div class="namebox">
        <h4><i class="fa fa-trash fa-lg" aria-hidden="true"></i>Trash</h4>
      </div>
      <div class="namebox">
        <h4><i class="fa fa-plus-square fa-lg" aria-hidden="true"></i> More</h4>
      </div>
      '
      <div class="folders">
        <h3>Folders</h3>
        <button type="button" value="Add">Add</button>
      </div>
      <div class="namebox">
        <h4><i class="fa fa-folder-o" aria-hidden="true"></i>Thank You</h4>
      </div>
      <div class="namebox">
        <h4><i class="fa fa-folder-o" aria-hidden="true"></i>Order Received</h4>
      </div>
      <div class="namebox">
        <h4>
          <i class="fa fa-folder-o" aria-hidden="true"></i>Transaction Complete
        </h4>
      </div>
      <div class="compose">
        <button type="button" class="compbtn">Compose</button>
      </div>
    </div>
    <div id="msg">
      <div class="namebox">
        <h4><i class="fa fa-folder-o" aria-hidden="true"></i>Thank You</h4>
      </div>
      <div class="namebox">
        <h4><i class="fa fa-folder-o" aria-hidden="true"></i>Order Received</h4>
      </div>
      <div class="namebox">
        <h4>
          <i class="fa fa-folder-o" aria-hidden="true"></i>Transaction Complete
        </h4>
      </div>
      <div class="compose">
        <button type="button" class="compbtn">Compose</button>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
#sidebar {
  position: fixed;
  top: 0;
  left: 0;
  height: 100vh;
  width: 15vw;
  background-color: #1e90ff;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
#email {
  width: 100%;
  background-color: #87cefa;
}
h3 {
  text-align: center;
  color: white;
}
#routes {
  position: fixed;
  left: 15vw;
  width: 25vw;
  height: 100%;
  background: whitesmoke;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding-bottom: 20px;
  box-sizing: border-box;
  overflow-y: scroll;
}
.namebox {
  width: 100%;
  padding-left: 100px;
  box-sizing: border-box;
}
.name {
  width: 100%;
  padding-left: 100px;
  box-sizing: border-box;
  margin-top: 80px;
}
.namebox:hover {
  background-color: rgba(100, 100, 100, 1);
  color: white;
  cursor: pointer;
}
i {
  padding-right: 20px;
}
.folders {
  padding: 10px 0px;
}
.folders h3 {
  color: black;
  display: inline;
}
button {
  margin-left: 60px;
  display: inline;
  border-radius: 20px;
  border: 0.5px solid black;
  padding: 5px 10px;
  cursor: pointer;
}
button:hover {
  background-color: rgba(100, 100, 100, 1);
  color: white;
}
.fa-folder-o {
  color: orange;
}
.feed {
  width: 100%;
  height: 100%;
  position: absolute;
  display: flex;
  align-items: flex-end;
  padding-bottom: 40px;
}
.feedbtn {
  margin-left: 20px;
  width: 80%;
  padding: 10px 10px;
  border-radius: 10px;
  border: 1.5px solid black;
  font-size: 1em;
}
.compose {
  width: 100%;
  text-align: center;
  margin-top: 10px;
}
.compbtn {
  margin-left: 10px;
  padding: 10px;
  width: 60%;
  font-size: 1em;
  border: 1.5px solid black;
  border-radius: 10px;
}
.compbtn:hover {
  background-color: #ff6347;
}
#msg {
  position: absolute;
  left: 40vw;
  width: 60vw;
  height: 140vh;
  background-color: blue;
}
</style>
