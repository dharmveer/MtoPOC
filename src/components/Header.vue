<template>
  <nb-container>
    <nb-header>
      <nb-left>
        <nb-button transparent>
          <nb-icon name="arrow-back" />
        </nb-button>
      </nb-left>
      <nb-body>
        <nb-title>{{screen}}</nb-title>
      </nb-body>
    </nb-header>
  </nb-container>
</template>
<script>

export default {
	props:{
		screen: {
			type:String,
			default:'Signature Sandwiches'
		}
	}
}
</script>