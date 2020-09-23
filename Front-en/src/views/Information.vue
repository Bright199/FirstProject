<template>
    <div class="vx-row">
        <!-- LONG FORM -->
    <div class="vx-col md:w-2/2 w-full mb-base">
      <vx-card title="Horizontal Form">
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Logo</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-upload class="w-full" v-model="input1" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Home Picture Path</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-upload class="w-full" v-model="input1" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Website</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input icon="website" placeholder="https://www.google.com" class="w-full" v-model="input1" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Email</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input icon="email" placeholder="bwinto@gamil.com" class="w-full" type="email" v-model="input2" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Event Name</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input icon="event" placeholder="Event Name" class="w-full" type="text" v-model="input2" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Date</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <datepicker placeholder="Select Date" v-model="date"></datepicker>
          </div>
        </div>

        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Color</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <input class="" type="color" v-model="input2" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Phone</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input icon="phone" placeholder="+90 535 56266 232" class="w-full" v-model="input3" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Address</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input placeholder="Lake Victoria street No. 2" class="w-full" v-model="input4" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Zip</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input placeholder="06070" class="w-full" v-model="input5" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Locality</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" v-model="input6" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Title</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" v-model="input7" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage main button text</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" v-model="input8" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage sub button text</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" v-model="input9" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage volunteer button text</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" v-model="input10" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Mobile</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" v-model="input11" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage rules button text</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" v-model="input12" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage faq button</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" v-model="input13" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage contact button text</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" v-model="input14" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Password</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <vs-input class="w-full" type="password" v-model="input15" />
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage rules text:</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <quill-editor v-model="content"></quill-editor>
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage faq text:</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <quill-editor v-model="content"></quill-editor>
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage contact text:</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <quill-editor v-model="content"></quill-editor>
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage volunteer text:</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <quill-editor v-model="content"></quill-editor>
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage subtext:</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <quill-editor v-model="content"></quill-editor>
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>Homepage main text:</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
            <quill-editor v-model="content"></quill-editor>
          </div>
        </div>
        <div class="vx-row mb-6">
          <div class="vx-col sm:w-1/3 w-full">
            <span>My Example:</span>
          </div>
          <div class="vx-col sm:w-2/3 w-full">
             <quill-editor v-model="content"></quill-editor>
          </div>
        </div>
        <!-- <div class="vx-row mb-6">
          <div class="vx-col sm:w-2/3 w-full ml-auto">
            <vs-checkbox class="inline-flex" v-model="check1">Remember Me</vs-checkbox>
          </div>
        </div> -->
     
        <div class="vx-row">
          <div class="vx-col sm:w-2/3 w-full ml-auto">
            <vs-button class="mr-3 mb-2">Save Changes</vs-button>
            <vs-button 
            color="warning" type="border" 
            class="mb-2" 
            @click="ResetField(); 
            check1 = false;">Cancel</vs-button>
          </div>
        </div>
      </vx-card>
    </div>
</div>
</template>

<script>
// require styles
import 'quill/dist/quill.core.css'
import 'quill/dist/quill.snow.css'
import 'quill/dist/quill.bubble.css'

import Datepicker from 'vuejs-datepicker'

import { quillEditor } from 'vue-quill-editor'

export default {
  components: {
    Datepicker,
    quillEditor
  },
  mounted () {
        
  },
  methods: {
    ResetField () {
      this.input1 = this.input2 = this.input3 = this.input4 = this.input5 = this.input6 = this.input7 = this.input8 = this.input9 = this.input10 = this.input11 = this.input12 = this.input13 = this.input14 = this.input15 = '' 
           
    }
  },
  data () {
    return {
      // eslint-disable-next-line quotes
      content: `...`,
      date: null,
      check1: '',
      check2: '',
      check3: '',
      check4: '',
      check5: '',
      check6: '',
      check7: '',
      input1: '',
      input2: '',
      input3: '',
      input4: '',
      input5: '',
      input6: '',
      input7: '',
      input8: '',
      input9: '',
      input10: '',
      input11: '',
      input12: '',
      input13: '',
      input14: '',
      input15: '',
      input16: '',
      input17: '',
      input18: '',
      input19: '',
      input20: '',
      input21: '',
      input22: '',
      input23: '',
      input24: '',
      input25: '',
      input26: '',
      input27: '',
      input28: '',
      input29: '',
      input30: ''  
    }
  }
}
</script>
<style lang="scss" scoped>
  .MyColor{
    display: none;
  }
</style>