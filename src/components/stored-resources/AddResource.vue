<template>
	<base-card>
		<form>
			<div class="form-control">
				<label for="title">Title</label>
				<input id="title" type="text" name="title" />
			</div>
			<div class="form-control">
				<label for="description">Description</label>
				<textarea id="description" name="description" rows="3" />
			</div>
			<div class="form-control">
				<label for="link">Link</label>
				<input id="link" type="url" name="link" />
			</div>
			<div>
				<base-button type="submit">Add Resource</base-button>
			</div>
		</form>
	</base-card>
</template>

<script>
export default {}
</script>

<style scoped>
label {
	font-weight: bold;
	display: block;
	margin-bottom: 0.5rem;
}

input,
textarea {
	display: block;
	width: 100%;
	font: inherit;
	padding: 0.15rem;
	border: 1px solid #ccc;
}

input:focus,
textarea:focus {
	outline: none;
	border-color: #3a0061;
	background-color: #f7ebff;
}

.form-control {
	margin: 1rem 0;
}
</style>
