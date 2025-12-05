<script>
  import { Plus, Bot, MessageCircle, Sparkle, Owl, Panda, Search, Moon, Flag, MoreHorizontal, MousePointerClick, ListFilter, MessageSquare } from '@lucide/svelte';
</script>

<!-- Hero -->
<header class="px-4 pt-8 pb-12 text-center">
	<div class="mb-6 inline-block p-3 bg-gradient-to-br from-primary/10 to-secondary/10 rounded-2xl">
		<div
			class="w-20 h-20 bg-gradient-to-br from-primary to-secondary rounded-xl flex items-center justify-center"
		>
			<Bot class="text-background w-10 h-10" />
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
		class="inline-block bg-primary hover:bg-secondary active:bg-accent text-background font-semibold py-4 px-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-200 text-lg w-full max-w-xs mx-auto flex items-center justify-center gap-2"
	>
		<Plus class="w-5 h-5" />
		Добавить в Max
	</a>
</header>

<!-- Models -->
<section class="px-4 pb-12">
	<h2 class="text-2xl font-bold text-center mb-8">Подключено</h2>
	<div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-4 max-w-4xl mx-auto">
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="w-12 h-12 rounded-xl bg-primary/10 flex items-center justify-center mb-2">
				<MessageCircle class="text-primary w-6 h-6" />
			</div>
			<span class="text-sm font-medium">ChatGPT</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="w-12 h-12 rounded-xl bg-secondary/10 flex items-center justify-center mb-2">
				<Sparkle class="text-secondary w-6 h-6" />
			</div>
			<span class="text-sm font-medium">Gemini</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="w-12 h-12 rounded-xl bg-accent/10 flex items-center justify-center mb-2">
				<Owl class="text-accent w-6 h-6" />
			</div>
			<span class="text-sm font-medium">Claude</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="w-12 h-12 rounded-xl bg-light/10 flex items-center justify-center mb-2">
				<Panda class="text-light w-6 h-6" />
			</div>
			<span class="text-sm font-medium">Qwen</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="w-12 h-12 rounded-xl bg-primary/10 flex items-center justify-center mb-2">
				<Search class="text-primary w-6 h-6" />
			</div>
			<span class="text-sm font-medium">DeepSeek</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="w-12 h-12 rounded-xl bg-secondary/10 flex items-center justify-center mb-2">
				<Moon class="text-secondary w-6 h-6" />
			</div>
			<span class="text-sm font-medium">Kimi</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="w-12 h-12 rounded-xl bg-accent/10 flex items-center justify-center mb-2">
				<Flag class="text-accent w-6 h-6 fill-current" />
			</div>
			<span class="text-sm font-medium">GigaChat</span>
		</div>
		<div class="bg-gray-50 rounded-xl p-4 flex flex-col items-center">
			<div class="w-12 h-12 rounded-xl bg-gray-200 flex items-center justify-center mb-2">
				<MoreHorizontal class="text-gray-600 w-6 h-6" />
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
					class="flex-shrink-0 w-10 h-10 rounded-full bg-primary flex items-center justify-center text-background font-bold mr-4 mt-0.5"
				>
					<MousePointerClick class="w-5 h-5" />
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
					class="flex-shrink-0 w-10 h-10 rounded-full bg-secondary flex items-center justify-center text-background font-bold mr-4 mt-0.5"
				>
					<ListFilter class="w-5 h-5" />
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
					class="flex-shrink-0 w-10 h-10 rounded-full bg-accent flex items-center justify-center text-background font-bold mr-4 mt-0.5"
				>
					<MessageSquare class="w-5 h-5" />
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
		<Bot class="w-5 h-5" />
		Открыть бота
	</a>
	<p class="text-xs text-gray-500 mt-4">Работает только в приложении Max</p>
</section>

<footer class="border-t border-gray-200 py-6 px-4 text-center text-sm text-gray-500">
	<p>Сервис не аффилирован с OpenAI, Google, Anthropic, Сбером. API — легальные.</p>
</footer>