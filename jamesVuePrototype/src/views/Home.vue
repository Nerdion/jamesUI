<template>
  <div class="home">
    <div id="mainPageContent" class="container-fluid">
      <p class="contextTitle">Lorem ipsum dolor</p><br>
      <div class="row my-2 justify-content-center">
        <button type="button" @click=openIpsum() class="btn btn-lg btn-primary col-md-2 col-4 text-center mr-4">ipsum</button>
        <button type="button" @click=openConsec() class="btn btn-lg btn-primary col-md-2 col-4 text-center ml-4">consec</button>
      </div>
      <div class="row justify-content-center">
        <div id="ipsumNav" class="col-md-5 col-10 form-group my-4">
          <input type="text" class="form-control" placeholder="totam rem aperiam"/>
          <input type="text" class="form-control" placeholder="totam rem aperiam"/>
          <button class="btn btn-lg btn-dark" onclick="window.location='/otherPageOne'">Show</button>
        </div>
        <div id="consecNav" class="col-8 my-4">
          <div class="row justify-content-center">
            <div class="col-12 col-md-4 mx-4 mt-3">
              <p><b>
                Duis aute irure dolor </b><i class="ml-5">More Info</i></p>
              <p>in reprehenderit in voluptate velit
              esse cillum dolore</p>
              <button class="btn btn-dark" onclick="window.location='/gettingStarted/one'">Select</button>
            </div>
            <div class="col-12 col-md-4 mx-4 mt-3">
              <p><b >Duis aute irure dolor </b><i class="ml-5">More Info</i></p>
              <p>
              in reprehenderit in voluptate velit
              esse cillum dolore</p>
              <button class="btn btn-dark" onclick="window.location='/gettingStarted/one'">Select</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="row text-center">
      <div class="col">
        <p class="lead">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt
        </p>
      </div>
    </div>
    <div class="row">
      <div class="col mt-4">
        <p style="font-size:24px">Excepteur sint occaecat cupidatat</p>
        <hr />
      </div>
    </div>
    <div class="row h-350">
      <div class="col-md-6 col-12 mt-3">
        <div class="roundBox sideBox">
          <p class="">You don’t have any chats at the moment</p>
          <div class="roundBox messageList">
            <i></i>
            <p>Sed ut perspiciatis</p>
          </div>
          <div class="roundBox messageList ">
            <i></i>
            <p>Sed ut perspiciatis</p>
          </div>
          <div class="roundBox messageList">
            <i></i>
            <p>Sed ut perspiciatis</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-12 mt-3">
        <div class="row">
          <div class="col roundBox sideBox-70"></div>
        </div>
        <div class="row">
          <div class="col roundBox sideBox-30">
            <div class="">
              <small>This is lorem ipsum</small>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row">
      <div class="col">
        <p class="topicTitle">Our AI System</p>
        <hr />
      </div>
    </div>
    <div class="row">
      <div class="col-4">
        <b class="">Fast</b>
      </div>
      <div class="col-4">
        <b class="">Reliable</b>
      </div>
      <div class="col-4">
        <b class="">Private</b>
      </div>
    <div class="mb-5"></div>
    </div>
  </div>

  <div class="container">
    <div class="m-5"></div>
    <div class="row">
      <div class="col">
        <p class="topicTitle">Why Setting Up Your Ad in TBD?</p>
        <p class="topicSubtitle">Welcome First Name, Last Name . Email Address</p><hr>
        <div class="m-5"></div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4">
        <b class="">Neque porro quisquam </b>
        <p class="">
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit
        </p>
      </div>
      <div class="col-md-4">
        <b class="">Neque porro quisquam</b>
        <p class="">
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit
        </p>
      </div>
      <div class="col-md-4">
        <b class="">Neque porro quisquam</b>
        <p class="">
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit
        </p>
      </div>
    </div>
    <div class="row">
      <div class="col">
      <div class="m-5"></div>
      <div class="my-5">
        <input type="button" class="btn btn-dark" value="Get Started" onclick="window.location='gettingStarted/one'"/>
      </div>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="m-5"></div>
    <div class="row">
      <div class="col">
        <p class="topicTitle">Why Setting Up Your Digital TBD Account?</p>
        <p class="topicSubtitle">Welcome First Name, Last Name . Email Address</p><hr>
        <div class="m-5"></div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4 col-12">
        <b class="">Neque porro quisquam </b>
        <p class="">
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit
        </p>
      </div>
      <div class="col-md-4 col-12">
        <b class="">Neque porro quisquam</b>
        <p class="">
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit
        </p>
      </div>
      <div class="col-md-4 col-12">
        <b class="">Neque porro quisquam</b>
        <p class="">
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit
        </p>
      </div>
    </div>
    <div class="row">
      <div class="col">
      <div class="m-5"></div>
      <div class="my-5">
        <input type="button" class="btn btn-dark" value="Get Started" />
      </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
  mounted() {
    document.querySelector("#ipsumNav").style.display = "none";
    document.querySelector("#consecNav").style.display = "none";
  },
  methods: {
    openIpsum() {
      document.querySelector("#ipsumNav").style.display = "block";
      document.querySelector("#consecNav").style.display = "none";
    },
    openConsec() {
      document.querySelector("#ipsumNav").style.display = "none";
      document.querySelector("#consecNav").style.display = "block";
    }
  }
};
</script>

<style lang="scss" scoped>

#otherOptionNav input {
  padding:2px 8vh !important;
  font-size:24px !important;
}

#mainPageContent {
  height: 100%;
  padding-top: 15%;
  padding-bottom: 10%;
}

.contextTitle {
  font-style: normal;
  font-weight: normal;
  font-size: 42px;
  line-height: 44px;
  text-align: center;
  color: #000000;
}

.roundBox {
  border: 1px solid black;
  border-radius: 10px;
}

.messageList {
  margin-top: 10px;
  padding-left: 10px;
}

.h-350 {
  padding-bottom: 150px !important;
  .sideBox {
    padding: 2rem;
  }
}

.sideBox-70 {
  margin-left:1rem;
  margin-right:1rem;
  padding-bottom: 160px;
  margin-bottom: 20px;
}
.sideBox-30 {
  margin-left:1rem;
  margin-right:1rem;
  padding-bottom: 50px;
}

.topicTitle {
  font-size: 24px;
}

.topicSubtitle {
  font-size:14px;
}

#ipsumNav input {
  margin:10px 0 !important;
}

#consecNav > div.row > div {
  border: 1px solid black;
  background-color: white;
  border-radius: 5px;
  padding:1em;
  button {
    border-radius: 5px;
  }
}
</style>
