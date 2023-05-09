
<!DOCTYPE html>
<html>
<head>
	<title>Filterable Text Boxes</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			background-color: #f0f0f0;
		}

		.container {
			max-width: 800px;
			margin: 0 auto;
			padding: 20px;
			background-color: #fff;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		}

		h1 {
			margin-top: 0;
			font-weight: normal;
			text-align: center;
			color: #333;
		}

		.filter-buttons {
			display: flex;
			justify-content: center;
			margin-bottom: 20px;
		}

		.filter-button {
			padding: 10px 20px;
			border: none;
			border-radius: 20px;
			background-color: #333;
			color: #fff;
			font-size: 18px;
			font-weight: bold;
			cursor: pointer;
			transition: background-color 0.2s ease;
			margin-right: 10px;
		}

		.filter-button:hover {
			background-color: #555;
		}

		.filter-button.active {
			background-color: #fff;
			color: #333;
			box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
		}

		.text-boxes {
			display: grid;
			grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
			grid-gap: 20px;
			margin-bottom: 20px;
		}

		.text-box {
			background-color: #fff;
			padding: 20px;
			box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
			height: 200px;
			overflow: hidden;
			transition: height 0.2s ease;
		}

		.text-box h2 {
			margin-top: 0;
			font-size: 24px;
			color: #333;
		}

		.text-box p {
			margin: 0;
			font-size: 16px;
			color: #666;
		}

		.text-box a {
			color: #333;
			font-weight: bold;
			text-decoration: none;
			transition: color 0.2s ease;
		}

		.text-box a:hover {
			color: #555;
		}

		.show {
			height: auto;
		}
	</style>
</head>
<body>
	<div class="container">
		<h1>Filterable Text Boxes</h1>
		<div class="filter-buttons">
			<button class="filter-button active" data-filter="category1">Category 1</button>
			<button class="filter-button" data-filter="category2">Category 2</button>
			<button class="filter-button" data-filter="category3">Category 3</button>
			<button class="filter-button" data-filter="category4">Category 4</button>
		</div>
		<div class="text-boxes">
			<div class="text-box" data-category="category1">
				<h2>Text Box 1</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ut lacus quis augue