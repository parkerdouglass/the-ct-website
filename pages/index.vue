<!-- 
  LANDING PAGE
 -->
<template>
  <div class="page">
    <div class="hero-container">
      <div class="hero-text">
        <span class="text">
          <p class="line-one">ZERO Censorship</p>
          <p class="line-two">ZERO Cost</p>
        </span>
      </div>
    </div>
    <div class="main-content">
      <div class="no-censorship-section">
        <v-row>
          <v-col cols="1">
            <v-icon class="chat-bubble-icon">mdi-message-outline</v-icon>
          </v-col>
          <v-col cols="9" class="text-col">
            <span class="nc-text">
              Tired of platform censorship? Welcome to The CT. We will never
              our beliefes here. <strong>What you hear is what we believe</strong>
            </span>
          </v-col>
        </v-row>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
  .hero-container{
    background-color: #292323;
    padding-top: 100px;
    padding-bottom: 100px;
    .hero-text{
      margin-left: 20px;
      .text{
        color: white;
        line-height: 9vh;
        font-size: 48px;
        .line-two{
          margin-left: 10vh;
        }
      }
    }
  }
  .main-content{
    margin:40px;
    .no-censorship-section{
      background-color:#0075FF;
      border: 1px solid #0075FF;
      border-radius: 4px;
      color: white;
      padding-top:20px;
      vertical-align: middle;
      .chat-bubble-icon{
        font-size: 150px;
        color: rgb(41, 28, 112);
        vertical-align: middle;
      }
    .text-col{
      padding-left: 150px;
      .nc-text{
        vertical-align: middle;
        line-height: 4.5vh;
        font-size: 18px;
      }
      }
    }
  }
</style>
