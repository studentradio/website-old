<script>
	let tailwind = '';
	export { tailwind as class };
</script>

<div class="relative inline-grid justify-center items-center grid-cols-1 grid-rows-1">
	<svg
		xmlns="http://www.w3.org/2000/svg"
		xmlns:xlink="http://www.w3.org/1999/xlink"
		viewBox="40 -40 360 500"
		class="{tailwind} col-span-1 row-span-1 row-start-1 col-start-1"
	>
		<defs>
			<linearGradient
				id="linear-gradient"
				x1="0.5"
				y1="1"
				x2="0.5"
				gradientUnits="objectBoundingBox"
			>
				<stop offset="0" stop-color="#e6007e" />
				<stop offset="0.41" stop-color="#e94e1b" />
				<stop offset="0.82" stop-color="#f39200" />
				<stop offset="1" stop-color="#f9b233" />
			</linearGradient>
			<linearGradient
				id="linear-gradient-2"
				x1="-0.023"
				y1="0.179"
				x2="0.722"
				y2="0.87"
				xlink:href="#linear-gradient"
			/>
			<linearGradient
				id="linear-gradient-3"
				x1="0.591"
				y1="0.954"
				x2="0.458"
				y2="-0.044"
				xlink:href="#linear-gradient"
			/>
		</defs>
		<g
			id="SRA_Masterbrand_Logo_FULL"
			data-name="SRA Masterbrand Logo FULL"
			transform="matrix(0.454, 0.891, -0.891, 0.454, 363.461, -17.219)"
			style="isolation: isolate"
		>
			<g id="Layer_1" data-name="Layer 1" transform="translate(0.005 11.522)">
				<g
					id="Group_1"
					data-name="Group 1"
					transform="translate(19.488)"
					style="mix-blend-mode: soft-light;isolation: isolate"
				>
					<path
						id="Path_1"
						data-name="Path 1"
						d="M49.48,514.344c0-96.845,1.762-295.712,1.98-298.346,1.722-15.366,13.857-31.977,35.534-31.391,15.837.439,28.032,6.787,40.84,13.574,36.425,19.281,73.108,38.16,109.553,57.423s72.969,38.416,108.879,58.356c18.965,10.519,40.147,17.927,55.667,33.6,12.59,12.805,13.956,33.459-.218,44.416-12.967,10.061-27.814,18.293-42.463,26.214C323.4,437.768,287.174,456.739,251.145,476c-30.13,16.116-60.042,32.6-90.41,48.331-19.8,10.3-39.751,20.854-60.715,28.885s-39.889-2.067-46.6-21.952C51.717,525.8,50.826,520.107,49.48,514.344Z"
						transform="translate(-49.48 -184.592)"
						fill="url(#linear-gradient)"
					/>
				</g>
				<g
					id="Group_2"
					data-name="Group 2"
					transform="translate(23.939 10.937)"
					style="mix-blend-mode: soft-light;isolation: isolate"
				>
					<path
						id="Path_2"
						data-name="Path 2"
						d="M53.59,521.967c6.674-96.73,21.92-295.224,22.331-297.842,2.76-15.249,15.853-31.12,37.186-29.29,15.657,1.373,27.2,8.439,39.378,15.963,34.622,21.418,69.519,42.434,104.161,63.815s69.382,42.635,103.515,64.712c18.006,11.624,38.38,20.283,52.628,36.85,11.567,13.455,11.489,34.233-3.249,44.356-13.485,9.263-28.692,16.476-43.684,23.652-36.7,17.427-73.746,34.251-110.619,51.349-30.825,14.315-61.455,29.015-92.5,42.946-20.3,9.153-40.65,18.471-61.866,25.244S61.732,559.33,56.369,539.1C55,533.537,54.51,527.7,53.59,521.967Z"
						transform="translate(-53.59 -194.691)"
						fill="url(#linear-gradient-2)"
					/>
				</g>
				<g
					id="Group_3"
					data-name="Group 3"
					transform="translate(0 26.397)"
					style="mix-blend-mode: soft-light;isolation: isolate"
				>
					<path
						id="Path_3"
						data-name="Path 3"
						d="M395.574,379.01c-11.294,11.5-24.645,21.33-37.84,30.977-32.232,23.623-64.969,46.64-97.453,70.043-27.167,19.515-54.063,39.4-81.5,58.562-17.95,12.527-35.9,25.347-55.227,35.746s-39.063,2.586-48.222-16.378c-2.561-5.264-4.192-11-6.229-16.4C56.236,445.22,31.553,247.2,31.494,244.554c-.349-15.5,9.237-33.417,30.388-35.343,15.524-1.412,28.176,3.5,41.527,8.767,37.976,14.893,76.165,29.565,114.161,44.421s76.068,29.712,113.714,45.412c19.851,8.272,41.43,13.187,58.6,26.979C403.821,345.978,407.9,366.447,395.574,379.01Z"
						transform="translate(-31.485 -208.966)"
						fill="url(#linear-gradient-3)"
					/>
				</g>
			</g>
		</g>
	</svg>
	<section
		class="text-center col-span-1 row-span-1 row-start-1 col-start-1 text-2xl text-white z-10"
	>
		<slot />
	</section>
</div>
