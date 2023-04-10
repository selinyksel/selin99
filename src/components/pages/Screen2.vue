<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="51eccb3c-5dcf-4973-9add-72cb40f84f49"
    v-bind:style="{'width':'100%','height':'auto','background':'#4AFF4AFF'}">
    <WCircleImage v-bind:blank="false" rounded="circle" stretch="none"
      imageUrl="https://picsum.photos/350/350/?image=58" v-bind:isEnabled="true" v-bind:thumbnail="false"
      blankColor="black" v-bind:aspectRatio="true" dataLoading="static"
      ncTooltipText="Please write a text to display in tooltip..."
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'update':{'type':'dataModelForDynamicType'},'propName':'imageUrl','displayName':'Value'}]}"
      ncClickBorderColor="black" ncHoverBorderColor="black" dataModelForDynamicType="string" position="relative"
      id="268e89e4-a4b1-48d7-8618-bcf4ee8bd235"
      v-bind:style="{'width':'100%','height':'100%','boxShadow':'','marginTop':'0px','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#4B74FF','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
  </DropZone>
</template>
<script>
export default {
  name: 'Screen2',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style lang="scss" scoped>
@media (min-width: 1024.05px){[id='51eccb3c-5dcf-4973-9add-72cb40f84f49'] {
             display: grid; 
             grid-template-columns: 35.5078125rem 27.34375rem 37.1484375rem;
             grid-template-rows: minmax(31.40625rem, max-content) minmax(27.34375rem, max-content) minmax(21.978759765625rem, max-content);
          }
[id='268e89e4-a4b1-48d7-8618-bcf4ee8bd235']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 1;
          }}

@media (min-width: 768.05px) and (max-width: 1024px){[id='51eccb3c-5dcf-4973-9add-72cb40f84f49'] {
             display: grid; 
             grid-template-columns: 32.91015625rem 34.1796875rem 32.91015625rem;
             grid-template-rows: minmax(39.2578125rem, max-content) minmax(34.1796875rem, max-content) minmax(3.125rem, max-content);
          }
[id='268e89e4-a4b1-48d7-8618-bcf4ee8bd235']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 1;
          }}

@media (min-width: 480.05px) and (max-width: 768px){[id='51eccb3c-5dcf-4973-9add-72cb40f84f49'] {
             display: grid; 
             grid-template-columns: 27.213541666666668rem 45.572916666666664rem 27.213541666666668rem;
             grid-template-rows: minmax(52.34375rem, max-content) minmax(45.572916666666664rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='268e89e4-a4b1-48d7-8618-bcf4ee8bd235']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 1;
          }}

@media (min-width: 375.05px) and (max-width: 480px){[id='51eccb3c-5dcf-4973-9add-72cb40f84f49'] {
             display: grid; 
             grid-template-columns: 13.541666666666664rem 72.91666666666667rem 13.541666666666664rem;
             grid-template-rows: minmax(83.75rem, max-content) minmax(72.91666666666667rem, max-content) minmax(5rem, max-content);
          }
[id='268e89e4-a4b1-48d7-8618-bcf4ee8bd235']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 1;
          }}

@media (min-width: 0px) and (max-width: 375px){[id='51eccb3c-5dcf-4973-9add-72cb40f84f49'] {
             display: grid; 
             grid-template-columns: 6.4rem 87.2rem 6.4rem;
             grid-template-rows: minmax(107.2rem, max-content) minmax(87.2rem, max-content) minmax(6.4rem, max-content);
          }
[id='268e89e4-a4b1-48d7-8618-bcf4ee8bd235']{
          grid-area: 2/2/3/3;
          
          aspect-ratio: 1;
          }}
</style>