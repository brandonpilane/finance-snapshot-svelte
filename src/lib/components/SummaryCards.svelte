<script lang="ts">
	import SummaryCard from '$lib/components/SummaryCard.svelte';
</script>

<!-- 
	Todo:
	- Make the card content dynamic
-->

<section class="flex w-full flex-row items-center justify-between px-8 py-10">
	<SummaryCard title="Net Worth" value="120450.00" change="+10%" trend="up" colour="#00cc66" />
	<SummaryCard title="Cash Balance" value="16500.00" change="-5%" trend="down" colour="#d90368" />
	<SummaryCard title="Credit Balance" value="12500.00" change="+5%" trend="up" colour="#f1c40f" />
	<SummaryCard
		title="This Month's Expenses"
		value="1275.95"
		change="-5%"
		trend="down"
		colour="#f75c03"
	/>
</section>
