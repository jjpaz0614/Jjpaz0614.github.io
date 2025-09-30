# Jjpaz0614.github.io
Espresso Mocha Cake 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ultimate Coffee Chocolate Layer Cake</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Custom configuration for Inter font -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f7;
            display: flex;
            justify-content: center;
            padding: 1rem;
        }
        /* Custom styles for the magazine card */
        .magazine-card {
            background-color: #ffffff;
            max-width: 900px;
            width: 100%;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
        }
        /* Custom styling for ingredient list for a slightly different look */
        .ingredient-list li {
            padding: 0.25rem 0;
            border-bottom: 1px dotted #ccc;
        }
    </style>
</head>
<body>

<div class="magazine-card rounded-xl overflow-hidden">
    <!-- Masthead / Title Section -->
    <header class="p-6 md:p-10 bg-gray-50 border-b border-gray-200">
        <p class="text-xs tracking-widest uppercase text-amber-600 mb-1 font-semibold">The Baker's Collection</p>
        <h1 class="text-4xl md:text-6xl font-extrabold text-gray-900 leading-tight">Ultimate Coffee Chocolate Layer Cake</h1>
        <p class="mt-3 text-lg text-gray-600 italic">A rich, moist chocolate base paired with a velvety espresso ganache and crowned with a fluffy, coffee-infused buttercream.</p>
        
        <!-- Stats -->
        <div class="mt-6 flex flex-wrap gap-4 text-sm font-medium text-gray-700">
            <span class="flex items-center">
                <svg class="w-4 h-4 mr-1 text-amber-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                Prep Time: 45 min
            </span>
            <span class="flex items-center">
                <svg class="w-4 h-4 mr-1 text-amber-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.276a11.955 11.955 0 010 17.552c-.783.783-2.316.48-2.316.48"></path></svg>
                Bake Time: 30 min
            </span>
            <span class="flex items-center">
                <svg class="w-4 h-4 mr-1 text-amber-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c1.657 0 3 .895 3 2s-1.343 2-3 2-3-.895-3-2 1.343-2 3-2z"></path></svg>
                Yield: One Layer Cake
            </span>
        </div>
    </header>

    <!-- Image Section - Prominent Feature -->
    <div class="relative h-96 w-full overflow-hidden">
        <!-- Using the filename 'image.png' which should display the latest uploaded image -->
        <img src="image.png" alt="Finished Coffee Chocolate Layer Cake with decorative rosettes" class="object-cover w-full h-full" onerror="this.onerror=null;this.src='https://placehold.co/900x384/444444/FFFFFF?text=Cake+Photo+Loading...';" />
        <div class="absolute bottom-0 right-0 p-3 bg-black bg-opacity-50 text-white text-xs rounded-tl-lg">Photo by You</div>
    </div>

    <!-- Main Recipe Content - Two Column Layout on Desktop, Stacked on Mobile -->
    <div class="p-6 md:p-10">

        <!-- 1. CAKE LAYERS -->
        <div class="mb-10 pb-6 border-b border-gray-200">
            <h2 class="text-3xl font-bold text-gray-800 mb-4 tracking-tight">1. Moist Chocolate Cake Layers</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Ingredients Column (1/3) -->
                <div class="md:col-span-1">
                    <h3 class="text-xl font-semibold text-gray-700 mb-3 border-b-2 border-amber-400 pb-1">Ingredients</h3>
                    <ul class="list-none p-0 ingredient-list text-sm text-gray-700">
                        <li><span class="font-bold">2 cups</span> All-Purpose Flour</li>
                        <li><span class="font-bold">2 cups</span> Granulated Sugar</li>
                        <li><span class="font-bold">¾ cup</span> Dark Cocoa Powder</li>
                        <li><span class="font-bold">2 tsp</span> Baking Powder</li>
                        <li><span class="font-bold">1½ tsp</span> Baking Soda</li>
                        <li><span class="font-bold">1 tsp</span> Salt</li>
                        <li><span class="font-bold">1 cup</span> Warm Water</li>
                        <li><span class="font-bold">1 cup</span> Sour Cream</li>
                        <li><span class="font-bold">½ cup</span> Vegetable Oil</li>
                        <li><span class="font-bold">2 large</span> Eggs</li>
                        <li><span class="font-bold">2 tsp</span> Vanilla Extract</li>
                        <li><span class="font-bold">1 tsp</span> Instant Espresso Powder</li>
                        <li><span class="font-bold">½ cup</span> Chocolate Simple Syrup</li>
                    </ul>
                </div>
                
                <!-- Instructions Column (2/3) -->
                <div class="md:col-span-2">
                    <h3 class="text-xl font-semibold text-gray-700 mb-3 border-b-2 border-amber-400 pb-1">Instructions</h3>
                    <ol class="list-decimal pl-6 space-y-3 text-base text-gray-700">
                        <li>**Prep:** Preheat oven to **350°F (175°C)**. Grease and flour your desired cake pans.</li>
                        <li>**Combine Dry:** In a large bowl, whisk together the flour, granulated sugar, cocoa powder, baking powder, baking soda, and salt.</li>
                        <li>**Combine Wet:** In a separate bowl, whisk together the warm water, sour cream, vegetable oil, eggs, vanilla extract, instant espresso powder, and chocolate simple syrup.</li>
                        <li>**Mix:** Pour the wet ingredients into the dry ingredients. **Whisk** until the batter is just smooth and lump-free. *Avoid overmixing.*</li>
                        <li>**Bake:** Pour the batter evenly into the prepared pans. Bake for approximately **30 minutes**, or until a wooden skewer comes out clean.</li>
                        <li>**Cool:** Let the cakes cool in the pans for 10-15 minutes before inverting them onto a wire rack to cool completely.</li>
                    </ol>
                </div>
            </div>
        </div>

        <!-- 2. COFFEE ESPRESSO GANACHE -->
        <div class="mb-10 pb-6 border-b border-gray-200">
            <h2 class="text-2xl font-bold text-gray-800 mb-4 tracking-tight">2. Coffee Espresso Ganache (Filling)</h2>
            <div class="md:flex md:space-x-8">
                <div class="mb-4 md:mb-0 md:w-1/3">
                    <h3 class="text-lg font-semibold text-gray-700 mb-2">Ingredients</h3>
                    <ul class="list-none p-0 text-sm text-gray-700 space-y-1">
                        <li><span class="font-bold">300 grams</span> Heavy Cream</li>
                        <li><span class="font-bold">2 Tbsp</span> Instant Coffee/Espresso</li>
                        <li><span class="font-bold">300 grams</span> Dark Chocolate Chips (1 bag)</li>
                    </ul>
                </div>
                <div class="md:w-2/3">
                    <h3 class="text-lg font-semibold text-gray-700 mb-2">Instructions</h3>
                    <ol class="list-decimal pl-6 space-y-2 text-base text-gray-700">
                        <li>**Heat Cream:** Heat the heavy cream until it just begins to simmer. Remove from heat.</li>
                        <li>**Mix Coffee:** Stir in the **instant coffee** until fully dissolved.</li>
                        <li>**Pour:** Place chocolate chips in a bowl. Pour the hot coffee cream mixture over the chips.</li>
                        <li>**Rest & Whisk:** Let it sit for **5 minutes**. Stir gently until smooth and glossy.</li>
                        <li>**Set:** Cool at room temperature until thick and spreadable.</li>
                    </ol>
                </div>
            </div>
        </div>

        <!-- 3. COFFEE BUTTERCREAM FROSTING -->
        <div class="mb-10 pb-6">
            <h2 class="text-2xl font-bold text-gray-800 mb-4 tracking-tight">3. Coffee Buttercream Frosting</h2>
            <p class="text-sm text-gray-500 mb-4">Yield: Approximately 3 Cups</p>
            <div class="md:flex md:space-x-8">
                <div class="mb-4 md:mb-0 md:w-1/3">
                    <h3 class="text-lg font-semibold text-gray-700 mb-2">Ingredients</h3>
                    <ul class="list-none p-0 text-sm text-gray-700 space-y-1">
                        <li><span class="font-bold">1½ tsp</span> Instant Coffee/Espresso Powder</li>
                        <li><span class="font-bold">1½ Tbsp</span> Whole Milk (room temperature)</li>
                        <li><span class="font-bold">1 Cup (226g)</span> Unsalted Butter (room temperature)</li>
                        <li><span class="font-bold">3½ Cups (420g)</span> Powdered Sugar</li>
                        <li><span class="font-bold">2 tsp</span> Pure Vanilla Extract</li>
                        <li><span class="font-bold">Pinch</span> of Salt</li>
                    </ul>
                </div>
                <div class="md:w-2/3">
                    <h3 class="text-lg font-semibold text-gray-700 mb-2">Instructions</h3>
                    <ol class="list-decimal pl-6 space-y-2 text-base text-gray-700">
                        <li>**Espresso Base:** Combine the instant coffee/espresso powder with the whole milk and set aside.</li>
                        <li>**Cream Butter:** Beat the room temperature butter on high for about **5 minutes** until creamy and smooth. Scrape down the bowl frequently.</li>
                        <li>**Add Sugar:** Turn the mixer to low. Gradually add the **powdered sugar**.</li>
                        <li>**Final Mix:** Add the vanilla, the coffee/espresso milk mixture, and salt. Mix on low until incorporated, then beat on medium-high for 1-2 minutes until light and fluffy.</li>
                    </ol>
                </div>
            </div>
        </div>

        <!-- 4. ASSEMBLY -->
        <div class="p-4 bg-amber-50 rounded-lg border-l-4 border-amber-400">
            <h2 class="text-2xl font-bold text-gray-800 mb-3 tracking-tight">4. Assembly</h2>
            <ol class="list-disc pl-6 space-y-2 text-base text-gray-700">
                <li>Place the first cake layer on your serving platter.</li>
                <li>Pipe or spread a generous layer of the **Coffee Espresso Ganache** onto the cake.</li>
                <li>Place the second cake layer on top.</li>
                <li>Use the **Coffee Buttercream** to frost the entire cake.</li>
                <li>Decorate with rosettes or other piping as desired!</li>
            </ol>
        </div>

    </div>
    
</div>

</body>
</html>
