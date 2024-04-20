<script setup>
import Header from './components/Header.vue'
import Buttonw from "./components/Buttonw.vue";
import EditorFiles from "./components/EditorFiles.vue";
import EditorWorkspace from "./components/EditorWorkspace.vue";
</script>

<template>
  <div class="mainT m">
    <Header/>
    <div id="back">
      <div id="dM">
        <div id="dR">
          <h1 id="h1" style="background: -webkit-linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(203,203,203,1) 75%, rgba(156,156,156,1) 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">
            The All-in-One SaaS Solution</h1>
          <div id="welD">
            <p class="txM welDI">Welcome to our powerful and intuitive Code Editor. Whether you're a seasoned developer or just starting your coding journey.</p>
            <div class="welDI" style="display: flex; align-items: center; padding-top: 2rem">
              <Buttonw msg="Try for free" id="btnWT"></Buttonw>
              <div id="welDR" style="display: flex; flex-direction: column; align-items: center; justify-content: start;">
                <p class="txM" style="font-size: 15px; margin-block-start: 0; margin-block-end: 0">Have a question?</p>
                <p class="txM" style="color: #f9f9f9; margin-block-start: 0; margin-block-end: 0">Schedule a demo</p>
              </div>
            </div>
          </div>


        </div>

        <div style="display: flex; width: 100%; justify-content: center; margin-top: 50px">
          <EditorFiles class="editor"/>
          <EditorWorkspace class="editor"/>
        </div>

        <h2 class="txM txMM" style="font-weight: lighter; padding-top: 60px">Companies of all sizes trust Crocus to</h2>
        <h2 class="txM txMM" style="font-weight: lighter; margin-bottom: 60px">deliver their most important emails.</h2>

        <!-- <div style="display: flex; width: 85%; justify-content: space-between; margin-top: 50px">
          <img src="./assets/expedia.svg" style="width: 15%">
          <img src="./assets/airbnb.svg" style="width: 15%">
          <img src="./assets/booking.svg" style="width: 15%">
          <img src="./assets/orbitz.svg" style="width: 15%">
          <img src="./assets/tripadvisor.svg" style="width: 15%">
        </div> -->
      </div>
    </div>

  </div>


</template>

<style scoped>

.m {
  flex-direction: column;
  background: #141414;
}

#back {
  background-image: url("assets/blurB.svg");
  background-repeat: no-repeat;
  background-position: right -500px top -20%;
}

#dM {
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  background-image: url("assets/blurY.svg");
  background-repeat: no-repeat;
  background-position: left 0% top -20%;
}

#dR {
  display: flex;
  width: 70%;
  padding: 0 15%;
  align-items: center;
  justify-content: center;
}

#btnWT {
  width: 150px; font-size: 20px; height: 50px
}

#h1 {
  font-size: 5vw; 
}

#welD {
  padding-left: 100px;
}

#welDR {
   padding-left: 40px
}

.txMM {
  font-size: 1.5rem;
}

@media (max-width: 756px) { 
  #dM {
    justify-content: center;
  }

  #dR {
    flex-direction: column;
    width: 85%;
    padding: 0 7.5%;
    justify-content: center;
  }

  #welD {
    padding: 0;
    justify-content: center;
  }

  .welDI {
    text-align: center;
    justify-content: center;
  }

  #welDR {
    padding-left: 15px;
  }

  #h1 {
    font-size: 40px;
  }


  #btnWT {
    width: 130px; font-size: 20px; height: 50px
  }

  .txMM {
    text-align: center;
    font-size: 20px;
  }
  
}

</style>
