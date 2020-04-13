---
layout: page
title: Crypto Updates
permalink: /crypto_update/
---
<br>In the simulation, you start with 10 ETH.<br>The objective is to maximize the ETH value by trading against altcoins 
in Binance.

<iframe width="775" height="525" frameborder="0" scrolling="no" src="//plotly.com/~vikramaditya91/109.embed"></iframe>

Last updated on: {{last_updated_on}} 
<table style="border:1px solid black;margin-left:auto;margin-right:auto;">
	<tbody>
	<tr>
		<td>Current ETH holding</td>
		<td>{{current_eth_holding}}</td>
	</tr>
	<tr>
		<td>Overall change of ETH</td>
		<td>{{overall_eth_percent}}</td>
	</tr>
	<tr>
		<td>Change in last week</td>
		<td>{{change_last_week}}</td>
	</tr>
	<tr>
		<td>Change in last month</td>
		<td>{{change_last_month}}</td>
	</tr>
    <tr>
		<td>Predicted ETH holding on<br>31 Dec 2020</td>
		<td>{{predicted_value_end_of_year}}</td>
	</tr>
	</tbody>
</table>
<a href="{{ '{{' }} site.baseurl {{ '}}' }}/crypto_history">Coin Update History</a>

<br>
<br>
Disclaimer:
Note that this is only a simulation. Although the price of the alt-coins are taken directly from the Binance API, the trades were not actually executed as this is still not ready for production.
Trading with crypto-currencies is considered speculative due to its volatile nature, and should be exercised with the utmost degree of caution.