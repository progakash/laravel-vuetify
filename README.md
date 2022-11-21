# laravel-vuetify
with install guideline


<laravel install>
-composer create-project laravel/laravel laravel-vue

<vue install>
-npm install vue@^2.7.13

setup vue:
-vue() add in webpack.mix.js
-create component within resources folder

config app.js:
-import vue
-import component file
-new Vue

blade file:
-setting blade file
-adding app.js and app.css using mix or asset

<vuetify install>
npm install vuetify
npm install sass@~1.32 sass-loader deepmerge -D

setup vuetify:
-import vuetify and using vuetify
-create folder plugins within resources
-create file vuetify.js
import Vue from 'vue'
import Vuetify from 'vuetify'
import 'vuetify/dist/vuetify.min.css'

Vue.use(Vuetify)

const opts = {}

export default new Vuetify(opts)

--write vuetify code in component


--npm run dev (2 times)

note:** vue-template-compiler and vue version should be same
