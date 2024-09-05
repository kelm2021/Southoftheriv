<script>
	import { Standings } from '$lib/components'

	export let data;
	const {standingsData, leagueTeamManagersData} = data;
</script>

<style>
	.holder {
		position: relative;
		z-index: 1;
		text-align: center;
	}
</style>

<div class="holder">
	<Standings {standingsData} {leagueTeamManagersData} />
</div>

<div class="holder">
	<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR_L2uJOH9jXVvouDI587NFSo8d4V6oxCkWSZ-9UTAAjuuL6pQRQg4z40vEkApRBAuteCTD9vvlub5J/pubhtml?gid=1459315646&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>
