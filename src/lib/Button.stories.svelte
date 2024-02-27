<script lang="ts" context="module">
	import { Story, Template } from '@storybook/addon-svelte-csf';
	import Button from './Button.svelte';

	export const meta = {
		component: Button,
		title: 'Button',
		tags: ['autodocs']
	};
</script>

<Template let:args>
	<Button {...args}>Hello World</Button>
</Template>

<Story name="Default" args={{ '--radius': '1rem' }} />
