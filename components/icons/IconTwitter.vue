<template>
	<svg viewBox="0 0 56.69 56.69" xmlns="http://www.w3.org/2000/svg" :width="width" :height="height">
		<g fill="currentColor">
			<path
				d="M18.32,50.32c20.41,0,31.57-16.91,31.57-31.57c0-0.48-0.01-0.96-0.03-1.43c2.17-1.56,4.05-3.52,5.53-5.75
		c-1.99,0.88-4.13,1.48-6.37,1.75c2.29-1.38,4.05-3.55,4.88-6.14c-2.14,1.27-4.52,2.2-7.05,2.7c-2.03-2.16-4.9-3.51-8.1-3.51
		c-6.13,0-11.09,4.97-11.09,11.09c0,0.87,0.1,1.71,0.28,2.53c-9.22-0.47-17.4-4.88-22.87-11.59c-0.95,1.64-1.5,3.54-1.5,5.57
		c0,3.85,1.96,7.25,4.94,9.24c-1.82-0.06-3.53-0.56-5.03-1.39c0,0.05,0,0.09,0,0.14c0,5.38,3.83,9.86,8.9,10.88
		c-0.93,0.25-1.91,0.39-2.92,0.39c-0.72,0-1.41-0.07-2.09-0.2c1.42,4.41,5.51,7.62,10.36,7.71c-3.8,2.98-8.58,4.75-13.78,4.75
		c-0.89,0-1.77-0.05-2.65-0.16C6.22,48.48,12.05,50.32,18.32,50.32"
			/>
		</g>
	</svg>
</template>

<script>
export default {
	name: "IconTwitter",
	props: {
		width: {
			type: [Number, String],
			default: 18,
		},
		height: {
			type: [Number, String],
			default: 18,
		},
	},
};
</script>

<style scoped>
svg {
	display: inline-block;
	vertical-align: baseline;
}
</style>
