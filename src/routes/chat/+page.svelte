<script lang="ts">
	import { Button } from '$lib/components/ui/button';
	import { Textarea } from '$lib/components/ui/textarea';
	import * as Avatar from '$lib/components/ui/avatar';
</script>

<section class="">
	<div class="mt-5 h-[700px] overflow-auto">
		<div class="my-10 flex gap-2">
			<span>
				<Avatar.Root class="h-8 w-8">
					<Avatar.Image src="https://github.com.png" alt="assistant" />
					<Avatar.Fallback>CS</Avatar.Fallback>
				</Avatar.Root>
			</span>
			<p>What Can I help you?</p>
		</div>
		<div class="my-10 flex gap-2">
			<span>
				<Avatar.Root class="h-8 w-8">
					<Avatar.Image src="https://github.com/shadcn.png" alt="assistant" />
					<Avatar.Fallback>CS</Avatar.Fallback>
				</Avatar.Root>
			</span>
			<p>
				This is where it's going to go I mean the prompt from the user,This is where it's going to
				go I mean the prompt from the user,This is where it's going to go I mean the prompt from the
				user
			</p>
		</div>
	</div>
	<footer class="grid w-full gap-2">
		<Textarea placeholder="Message Cinematic Stream" class="resize-none" />
		<Button class="w-40">Send message</Button>
	</footer>
</section>
