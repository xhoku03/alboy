<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com?plugins=forms,typography"></script>
		<script src="https://unpkg.com/unlazy@0.11.3/dist/unlazy.with-hashing.iife.js" defer init></script>
		<script type="text/javascript">
			window.tailwind.config = {
				darkMode: ['class'],
				theme: {
					extend: {
						colors: {
							border: 'hsl(var(--border))',
							input: 'hsl(var(--input))',
							ring: 'hsl(var(--ring))',
							background: 'hsl(var(--background))',
							foreground: 'hsl(var(--foreground))',
							primary: {
								DEFAULT: 'hsl(var(--primary))',
								foreground: 'hsl(var(--primary-foreground))'
							},
							secondary: {
								DEFAULT: 'hsl(var(--secondary))',
								foreground: 'hsl(var(--secondary-foreground))'
							},
							destructive: {
								DEFAULT: 'hsl(var(--destructive))',
								foreground: 'hsl(var(--destructive-foreground))'
							},
							muted: {
								DEFAULT: 'hsl(var(--muted))',
								foreground: 'hsl(var(--muted-foreground))'
							},
							accent: {
								DEFAULT: 'hsl(var(--accent))',
								foreground: 'hsl(var(--accent-foreground))'
							},
							popover: {
								DEFAULT: 'hsl(var(--popover))',
								foreground: 'hsl(var(--popover-foreground))'
							},
							card: {
								DEFAULT: 'hsl(var(--card))',
								foreground: 'hsl(var(--card-foreground))'
							},
						},
					}
				}
			}
		</script>
		<style type="text/tailwindcss">
			@layer base {
				:root {
					--background: 0 0% 100%;
--foreground: 0 0% 3.9%;
--card: 0 0% 100%;
--card-foreground: 0 0% 3.9%;
--popover: 0 0% 100%;
--popover-foreground: 0 0% 3.9%;
--primary: 0 72.2% 50.6%;
--primary-foreground: 0 85.7% 97.3%;
--secondary: 0 0% 96.1%;
--secondary-foreground: 0 0% 9%;
--muted: 0 0% 96.1%;
--muted-foreground: 0 0% 45.1%;
--accent: 0 0% 96.1%;
--accent-foreground: 0 0% 9%;
--destructive: 0 84.2% 60.2%;
--destructive-foreground: 0 0% 98%;
--border: 0 0% 89.8%;
--input: 0 0% 89.8%;
--ring: 0 72.2% 50.6%;
--radius: 0.4rem;
				}
				.dark {
					--background: 0 0% 3.9%;
--foreground: 0 0% 98%;
--card: 0 0% 3.9%;
--card-foreground: 0 0% 98%;
--popover: 0 0% 3.9%;
--popover-foreground: 0 0% 98%;
--primary: 0 72.2% 50.6%;
--primary-foreground: 0 85.7% 97.3%;
--secondary: 0 0% 14.9%;
--secondary-foreground: 0 0% 98%;
--muted: 0 0% 14.9%;
--muted-foreground: 0 0% 63.9%;
--accent: 0 0% 14.9%;
--accent-foreground: 0 0% 98%;
--destructive: 0 62.8% 30.6%;
--destructive-foreground: 0 0% 98%;
--border: 0 0% 14.9%;
--input: 0 0% 14.9%;
--ring: 0 72.2% 50.6%;
				}
			}
		</style>
  </head>
  <body>
    <div class="bg-background text-primary-foreground min-h-screen flex flex-col items-center justify-center">
    <header class="w-full bg-primary py-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">Alboy</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#" class="text-primary-foreground hover:underline">Home</a></li>
                    <li><a href="#" class="text-primary-foreground hover:underline">Shop</a></li>
                    <li><a href="#" class="text-primary-foreground hover:underline">About</a></li>
                    <li><a href="#" class="text-primary-foreground hover:underline">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
<main class="container mx-auto my-8">
    <section class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div>
            <h2 class="text-3xl font-bold mb-4">Discover Our Collection</h2>
            <p class="text-lg mb-4">Explore the latest trends in fashion.</p>
            <a href="#" class="bg-primary text-primary-foreground py-2 px-4 rounded-lg hover:bg-primary/80 transition">Shop Now</a>
        </div>
        <div>
            <img src="https://placehold.co/400x300/0000FF/FFFFFF?text=Alboy%20Clothing" alt="Alboy Clothing" class="rounded-lg">
        </div>
    </section>

    <section class="my-8">
        <h2 class="text-3xl font-bold mb-4">Featured Products</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
            <div class="bg-card p-4 rounded-lg">
                <img src="https://placehold.co/200x200/000000/FFFFFF?text=Product%201" alt="Product 1" class="rounded-lg">
                <h3 class="text-lg font-bold my-2">Product 1</h3>
                <p class="text-sm text-muted-foreground">Description of Product 1</p>
            </div>
            <div class="bg-card p-4 rounded-lg">
                <img src="https://placehold.co/200x200/000000/FFFFFF?text=Product%202" alt="Product 2" class="rounded-lg">
                <h3 class="text-lg font-bold my-2">Product 2</h3>
                <p class="text-sm text-muted-foreground">Description of Product 2</p>
            </div>
            <div class="bg-card p-4 rounded-lg">
                <img src="https://placehold.co/200x200/000000/FFFFFF?text=Product%203" alt="Product 3" class="rounded-lg">
                <h3 class="text-lg font-bold my-2">Product 3</h3>
                <p class="text-sm text-muted-foreground">Description of Product 3</p>
            </div>
        </div>
    </section>
</main>

<footer class="w-full bg-primary py-4 mt-auto">
    <div class="container mx-auto text-primary-foreground text-center">
        <p>&copy; 2023 Alboy Clothing. All Rights Reserved.</p>
    </div>
</footer>
</div>
<div class="bg-background text-primary-foreground min-h-screen flex flex-col items-center justify-center">
    <header id="header" class="w-full bg-primary py-4 fixed top-0 left-0 right-0 transition-transform duration-300">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">Alboy</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#" class="text-primary-foreground hover:underline">Home</a></li>
                    <li><a href="#" class="text-primary-foreground hover:underline">Shop</a></li>
                    <li><a href="#" class="text-primary-foreground hover:underline">About</a></li>
                    <li><a href="#" class="text-primary-foreground hover:underline">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main class="container mx-auto my-8 pt-20"> 
        <section class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div>
                <h2 class="text-3xl font-bold mb-4">Discover Our Collection</h2>
                <p class="text-lg mb-4">Explore the latest trends in fashion.</p>
                <a href="#" class="bg-primary text-primary-foreground py-2 px-4 rounded-lg hover:bg-primary/80 transition">Shop Now</a>
            </div>
            <div>
                <img src="https://placehold.co/400x300/0000FF/FFFFFF?text=Alboy%20Clothing" alt="Alboy Clothing" class="rounded-lg">
            </div>
        </section>
        <section class="my-8">
            <h2 class="text-3xl font-bold mb-4">Featured Products</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <div class="bg-card p-4 rounded-lg">
                    <img src="https://placehold.co/200x200/000000/FFFFFF?text=Product%201" alt="Product 1" class="rounded-lg">
                    <h3 class="text-lg font-bold my-2">Product 1</h3>
                    <p class="text-sm text-muted-foreground">Description of Product 1</p>
                </div>
                <div class="bg-card p-4 rounded-lg">
                    <img src="https://placehold.co/200x200/000000/FFFFFF?text=Product%202" alt="Product 2" class="rounded-lg">
                    <h3 class="text-lg font-bold my-2">Product 2</h3>
                    <p class="text-sm text-muted-foreground">Description of Product 2</p>
                </div>
                <div class="bg-card p-4 rounded-lg">
                    <img src="https://placehold.co/200x200/000000/FFFFFF?text=Product%203" alt="Product 3" class="rounded-lg">
                    <h3 class="text-lg font-bold my-2">Product 3</h3>
                    <p class="text-sm text-muted-foreground">Description of Product 3</p>
                </div>
            </div>
        </section>
    </main>
    <footer class="w-full bg-primary py-4 mt-auto">
        <div class="container mx-auto text-primary-foreground text-center">
            <p>&copy; 2023 Alboy Clothing. All Rights Reserved.</p>
        </div>
    </footer>
</div>

<script>
    let lastScrollTop = 0;
    const header = document.getElementById('header');

    window.addEventListener('scroll', () => {
        const scrollTop = window.pageYOffset || document.documentElement.scrollTop;
        if (scrollTop > lastScrollTop) {
            // Scrolling down
            header.style.transform = 'translateY(-100%)';
        } else {
            // Scrolling up
            header.style.transform = 'translateY(0)';
        }
        lastScrollTop = scrollTop;
    });
</script>

  </body>
</html>
