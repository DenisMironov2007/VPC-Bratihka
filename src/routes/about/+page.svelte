<script>
	import { fade } from 'svelte/transition';
	let visible = true;
</script>

<h1 class="h4">Расписание занятий</h1>

<div class="blok">
	<label>
		<input type="checkbox" class="custom-checkbox" bind:checked={visible}/>
		Расписание на июль 2023 г
	</label>
	{#if visible}
	<div  transition:fade>
			<table>
				<tr  class="type">
					<td colspan="5">Расписание занятий с курсантами старшей группы ВПК Братишка на июль 2023 г</td>
				</tr>
				<tr>
					<td>Число</td>
					<td>День</td>
					<td>Часы</td>
					<td>Занятие</td>
					<td>Место проведения</td>
				</tr>
				<tr>
					<td>3</td>
					<td>пн.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>4</td>
					<td>вт.</td>
					<td>18.00-20.00</td>
					<td>ТСП. Лазертаг</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>5</td>
					<td>ср.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>6</td>
					<td>чт.</td>
					<td>18.00-20.00</td>
					<td>Огневая. Страйкбол</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>7</td>
					<td>пт.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>8</td>
					<td>сб.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>9</td>
					<td>вс.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>10</td>
					<td>пн.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>11</td>
					<td>вт.</td>
					<td>18.00-20.00</td>
					<td>ТСП. Лазертаг</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>12</td>
					<td>ср.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>13</td>
					<td>чт.</td>
					<td>18.00-20.00</td>
					<td>Огневая. Страйкбол</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>14</td>
					<td>пт.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>15</td>
					<td>сб.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>16</td>
					<td>вс.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>17</td>
					<td>пн.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>18</td>
					<td>вт.</td>
					<td>18.00-20.00</td>
					<td>ТСП. Лазертаг</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>19</td>
					<td>ср.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>20</td>
					<td>чт.</td>
					<td>18.00-20.00</td>
					<td>Огневая. Страйкбол</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>21</td>
					<td>пт.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>22</td>
					<td>сб.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>23</td>
					<td>вс.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>24</td>
					<td>пн.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>25</td>
					<td>вт.</td>
					<td>18.00-20.00</td>
					<td>ТСП. Лазертаг</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>26</td>
					<td>ср.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>27</td>
					<td>чт.</td>
					<td>18.00-20.00</td>
					<td>Огневая. Страйкбол</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>28</td>
					<td>пт.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>29</td>
					<td>сб.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>30</td>
					<td>вс.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>31</td>
					<td>пн.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
			</table>
		</div>
	{/if}
</div>