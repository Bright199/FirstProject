<template>
    <div>
        <vs-row>
            <vs-col vs-type="flex" vs-justify="flex-start" vs-align="center" vs-w="12">
                <h3 >FAQ Management</h3>
            </vs-col>
            <vs-col vs-type="flex" vs-justify="flex-end" vs-align="center" vs-w="12">
                <vs-button @click="popupActivo=true" color="primary" type="border" class="">New Question</vs-button>
                <vs-popup class="holamundo"  title="Lorem ipsum dolor sit amet" :active.sync="popupActivo">
                <h1>New Question will be here!</h1>
            </vs-popup>
            </vs-col>
        </vs-row>
        <br>
        <!-- LIST OF QUESTION -->
         <vs-list>
            <vs-list-item subtitle="An excellent companion">
                <vs-button radius type="gradient" icon="edit" class="Styles"></vs-button>
                <vs-button radius color="danger" type="gradient" icon="delete"></vs-button>
            </vs-list-item>
            <vs-list-item subtitle="An excellent companion">
                <vs-button radius type="gradient" icon="edit" class="Styles"></vs-button>
                <vs-button radius color="danger" type="gradient" icon="delete"></vs-button>
            </vs-list-item>
        </vs-list>
    </div>
</template>
<script>
export default {
  data () {
    return {
      popupActivo:false
    }
  }
}
</script>
<style lang="scss" scoped>
    .Styles{
        float:left;
        margin-right: 10px
    }
</style>