<template>
	<div class="hello show-grid">
		<div class="row ">
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
			<div class="col-md-1">.col-md-1</div>
		</div>
		<div class="row">
			<div class="col-md-8">.col-md-8</div>
			<div class="col-md-4">.col-md-4</div>
		</div>
		<div class="row">
			<div class="col-md-4">.col-md-4</div>
			<div class="col-md-4">.col-md-4</div>
			<div class="col-md-4">.col-md-4</div>
		</div>
		<div class="row">
			<div class="col-md-6">.col-md-6</div>
			<div class="col-md-6">.col-md-6</div>
		</div>
		<div class="row">
			<div class="col-lg-6">
				<div class="input-group">
					<span class="input-group-btn">
		      		 	<button class="btn btn-default" type="button">-</button>
		      		</span>
					<input type="text" class="form-control" placeholder="2">
					<span class="input-group-btn">
		       			<button class="btn btn-default" type="button">+</button>
		      		</span>
				</div>
			</div>
		</div>
		<form>
			<div class="form-group">
				<label for="exampleInputEmail1">Email address</label>
				<input type="email" class="form-control" id="exampleInputEmail1" placeholder="Email">
			</div>
			<div class="form-group">
				<label for="exampleInputPassword1">Password</label>
				<input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
			</div>
			<div class="form-group">
				<label for="exampleInputFile">File input</label>
				<input type="file" id="exampleInputFile">
				<p class="help-block">Example block-level help text here.</p>
			</div>
			<div class="checkbox">
				<label>
      				<input type="checkbox"> Check me out
    			</label>
			</div>
			<button type="submit" class="btn btn-default">Submit</button>
		</form>
	</div>
</template>

<script>
	export default {
		name: 'HelloWorld',
		data() {

		}
	}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	@import url("../../static/css/HellowWorld.css");
</style>