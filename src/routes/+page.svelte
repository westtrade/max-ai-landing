<script>
	import PlusIcon from '@lucide/svelte/icons/plus';
	import BotIcon from '@lucide/svelte/icons/bot';
	import MessageCircleIcon from '@lucide/svelte/icons/message-circle';
	import SparkleIcon from '@lucide/svelte/icons/sparkle';
	import BirdIcon from '@lucide/svelte/icons/bird';
	import PandaIcon from '@lucide/svelte/icons/panda';
	import SearchIcon from '@lucide/svelte/icons/search';
	import MoonIcon from '@lucide/svelte/icons/moon';
	import FlagIcon from '@lucide/svelte/icons/flag';
	import CircleEllipsisIcon from '@lucide/svelte/icons/circle-ellipsis';
	import MousePointerClickIcon from '@lucide/svelte/icons/mouse-pointer-click';
	import ListFilterIcon from '@lucide/svelte/icons/list-filter';
	import MessageSquareIcon from '@lucide/svelte/icons/message-square';
</script>

<!-- Hero -->
<header class="px-4 pt-8 pb-12 text-center">
	<div class="mb-6 inline-block p-3 bg-linear-to-br from-primary/10 to-secondary/10 rounded-2xl">
		<div
			class="size-20 bg-linear-to-br from-primary to-secondary rounded-xl flex items-center justify-center"
		>
			<BotIcon class="text-background size-10" />
		</div>
	</div>
	<h1 class="text-3xl md:text-4xl font-bold max-w-lg mx-auto mb-4">
		<span class="text-primary">350+</span> ИИ-моделей — в одном боте
	</h1>
	<p class="text-gray-600 max-w-md mx-auto mb-8">
		ChatGPT, Gemini, Claude, GigaChat и другие — прямо в Max. Без регистрации на сайтах.
	</p>
	<a
		href="https://max.ru/id482613900020_bot"
		target="_blank"
		class="bg-primary hover:bg-secondary active:bg-accent text-background font-semibold py-4 px-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-200 text-lg w-full max-w-xs mx-auto flex items-center justify-center gap-2"
	>
		<PlusIcon class="size-5" />
		Добавить в Max
	</a>
</header>

<!-- Models -->
<section class="px-4 pb-12">
	<h2 class="text-2xl font-bold text-center mb-8">Подключено</h2>
	<div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-4 max-w-4xl mx-auto">
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="size-12 rounded-xl bg-primary/10 flex items-center justify-center mb-2">
				<MessageCircleIcon class="text-primary size-6" />
			</div>
			<span class="text-sm font-medium">ChatGPT</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="size-12 rounded-xl bg-secondary/10 flex items-center justify-center mb-2">
				<SparkleIcon class="text-secondary size-6" />
			</div>
			<span class="text-sm font-medium">Gemini</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="size-12 rounded-xl bg-accent/10 flex items-center justify-center mb-2">
				<BirdIcon class="text-accent size-6" />
			</div>
			<span class="text-sm font-medium">Claude</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="size-12 rounded-xl bg-light/10 flex items-center justify-center mb-2">
				<PandaIcon class="text-light size-6" />
			</div>
			<span class="text-sm font-medium">Qwen</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="size-12 rounded-xl bg-primary/10 flex items-center justify-center mb-2">
				<SearchIcon class="text-primary size-6" />
			</div>
			<span class="text-sm font-medium">DeepSeek</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="size-12 rounded-xl bg-secondary/10 flex items-center justify-center mb-2">
				<MoonIcon class="text-secondary size-6" />
			</div>
			<span class="text-sm font-medium">Kimi</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="size-12 rounded-xl bg-accent/10 flex items-center justify-center mb-2">
				<FlagIcon class="text-accent size-6 fill-current" />
			</div>
			<span class="text-sm font-medium">GigaChat</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="size-12 rounded-xl bg-gray-200 flex items-center justify-center mb-2">
				<CircleEllipsisIcon class="text-gray-600 size-6" />
			</div>
			<span class="text-sm font-medium">и другие</span>
		</div>
	</div>
</section>

<!-- Steps -->
<section class="bg-gray-50 py-12 px-4">
	<div class="max-w-4xl mx-auto">
		<h2 class="text-2xl font-bold text-center mb-10">Как это работает</h2>
		<div class="space-y-6">
			<div class="flex items-start">
				<div
					class="flex-shrink-0 size-10 rounded-full bg-primary flex items-center justify-center text-background font-bold mr-4 mt-0.5"
				>
					<MousePointerClickIcon class="size-5" />
				</div>
				<div>
					<h3 class="font-semibold text-lg mb-1">Найдите бота</h3>
					<p class="text-gray-600">
						В поиске Max: <code class="bg-gray-200 px-1.5 py-0.5 rounded text-xs"
							>@id482613900020_bot</code
						>
					</p>
				</div>
			</div>
			<div class="flex items-start">
				<div
					class="flex-shrink-0 size-10 rounded-full bg-secondary flex items-center justify-center text-background font-bold mr-4 mt-0.5"
				>
					<ListFilterIcon class="size-5" />
				</div>
				<div>
					<h3 class="font-semibold text-lg mb-1">Выберите модель</h3>
					<p class="text-gray-600">
						Команда <code class="bg-gray-200 px-1.5 py-0.5 rounded text-xs">/model</code> → 350+ вариантов
					</p>
				</div>
			</div>
			<div class="flex items-start">
				<div
					class="flex-shrink-0 size-10 rounded-full bg-accent flex items-center justify-center text-background font-bold mr-4 mt-0.5"
				>
					<MessageSquareIcon class="size-5" />
				</div>
				<div>
					<h3 class="font-semibold text-lg mb-1">Пишите — как в чате</h3>
					<p class="text-gray-600">Оплата — только за токены. Первые 10 000 — бесплатно.</p>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- Final CTA -->
<section class="px-4 py-12 text-center">
	<h2 class="text-2xl font-bold mb-4">Прямо сейчас — бесплатно</h2>
	<p class="text-gray-600 max-w-md mx-auto mb-6">
		Нет карты? Нет проблем. Достаточно аккаунта в Max.
	</p>
	<a
		href="https://max.ru/id482613900020_bot"
		target="_blank"
		class="inline-block bg-gradient-to-r from-primary to-secondary hover:from-secondary hover:to-accent text-background font-semibold py-4 px-8 rounded-xl shadow-lg hover:shadow-xl transition-all duration-200 text-lg w-full max-w-xs mx-auto flex items-center justify-center gap-2"
	>
		<BotIcon class="size-5" />
		Открыть бота
	</a>
	<p class="text-xs text-gray-500 mt-4">Работает только в приложении Max</p>
</section>

<footer class="border-t border-gray-200 py-6 px-4 text-center text-sm text-gray-500">
	<p>Сервис не аффилирован с OpenAI, Google, Anthropic, Сбером. API — легальные.</p>
</footer>
