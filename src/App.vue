<template>
  <div id="app">
    <div class="punch">
        <p>
            Seriously, just disable SELinux.<br>
            <a href="https://www.youtube.com/watch?v=_WOKRaM-HI4">Learn how to use it</a> and realise it's shit then turn it off.
        </p>
        <p>
            Every time you run <span style="font-family: monospace">setenforce 0</span>, you fix all your problems<br>
            Fuck <a href="https://people.redhat.com/dwalsh/">Dan Walsh</a> for making this piece of shit
        </p>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  metaInfo: {
      title: 'Disable SELinux'
  }
}
</script>

<style>

        body {
            background-color: #FFFFFF;
            font-weight: bold;
            font-family: monospace;
        }
        div.punch {
            font-size: 36px;
            position: absolute;
            top: 50%;
            margin-top: -200px;
            width: 99%;
            text-align: center;
        }
        div.info {
            font-size: 16px;
            position: absolute;
            bottom: 50px;
            width: 99%;
            text-align: center;
        }
        div.footer {
            font-size: 10px;
            position: absolute;
            bottom: 5px;
            width: 99%;
            text-align: center;
        }
</style>
