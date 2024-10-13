<template>
  <div class="min-h-[calc(100vh-150px)] text-[16px] md:bg-[hsl(30,54%,90%)] md:p-20 md:flex md:justify-center">
    <div class="md:bg-[hsl(0,0%,100%)] md:rounded p-10 md:w-[70%]">
      <img class="rounded mb-5" src="/images/image-omelette.jpeg" alt="Omelette Image">
      <div class="p-5 md:p-0">
        <h1 style="font-family: Outfit;" class="font-[600] text-[30px] mb-5">
          Simple Omelette Recipe
        </h1>
        <p class="mb-5">
          An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked
          to perfection, optionally filled with your choice of cheese, vegetables, or meats.
        </p>
        <div class="bg-[hsl(330,100%,98%)] p-5 mb-5">
          <h1 class="mb-5 text-[20px] font-[500] text-[hsl(332,51%,32%)]">
            Preparation time
          </h1>
          <ul class="list-disc ml-4 space-y-2">
            <li class="pl-4">
              <span style="font-family: Outfit;" class="font-[600]">Total:</span> Approximately 10 minutes
            </li>
            <li class="pl-4">
              <span style="font-family: Outfit;" class="font-[600]">Preparation:</span> 5 minutes
            </li>
            <li class="pl-4">
              <span style="font-family: Outfit;" class="font-[600]">Cooking:</span> 5 minutes
            </li>
          </ul>
        </div>
        <div class="mb-5 p-5">
          <h1 style="font-family: Outfit;" class="text-[25px] font-[600] text-[hsl(332,51%,32%)] mb-5">
            Ingredients
          </h1>
          <ul class="list-disc space-y-2">
            <li class="pl-4">
              2-3 large eggs
            </li>
            <li class="pl-4">
              Salt, to taste
            </li>
            <li class="pl-4">
              Pepper, to taste
            </li>
            <li class="pl-4">
              1 tablespoon of butter or oil
            </li>
            <li class="pl-4">
              Optional fillings: cheese, diced vegetables, cooked meats, herbs
            </li>
          </ul>
        </div>
        <hr class="mb-5">
        <div class="p-5">
          <h1 style="font-family: Outfit;" class="text-[25px] font-[600] text-[hsl(332,51%,32%)] mb-5">
            Instructions
          </h1>
          <ol class="list-disc">
            <li class="pl-4 mb-2">
              <span style="font-family: Outfit;" class="font-[600]">Beat the eggs:</span> In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed.
              You can add a tablespoon of water or milk for a fluffier texture.
            </li>
            <li class="pl-4 mb-2">
              <span style="font-family: Outfit;" class="font-[600]">Heat the pan:</span> Place a non-stick frying pan over medium heat and add butter or oil.
            </li>
            <li class="pl-4 mb-2">
              <span style="font-family: Outfit;" class="font-[600]">Cook the omelette:</span> Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure
              the eggs evenly coat the surface.
            </li>
            <li class="pl-4 mb-2">
              <span style="font-family: Outfit;" class="font-[600]">Add fillings (optional):</span> When the eggs begin to set at the edges but are still slightly runny in the
              middle, sprinkle your chosen fillings over one half of the omelette.
            </li>
            <li class="pl-4 mb-2">
              <span style="font-family: Outfit;" class="font-[600]">Fold and serve:</span> As the omelette continues to cook, carefully lift one edge and fold it over the
              fillings. Let it cook for another minute, then slide it onto a plate.
            </li>
            <li class="pl-4 mb-2">
              <span style="font-family: Outfit;" class="font-[600]">Enjoy:</span> Serve hot, with additional salt and pepper if needed.
            </li>
          </ol>
        </div>
        <div class="p-5">
          <h1 style="font-family: Outfit;" class="text-[25px] font-[600] text-[hsl(332,51%,32%)] mb-5">
            Nutrition
          </h1>
          <p class="mb-5">
            The table below shows nutritional values per serving without the additional fillings.
          </p>
          <table>
            <tbody>
              <tr class="border-b-2 ">
                <td class="px-10 py-2">
                  Calories
                </td>
                <td class="px-10 py-2 font-[600] text-[hsl(332,51%,32%)]">
                  227kcal
                </td>
              </tr>
              <tr class="border-b-2">
                <td class="px-10 py-2">
                  Carbs
                </td>
                <td class="px-10 py-2 font-[600] text-[hsl(332,51%,32%)]">
                  0g
                </td>
              </tr>
              <tr class="border-b-2">
                <td class="px-10 py-2">
                  Protein
                </td>
                <td class="px-10 py-2 font-[600] text-[hsl(332,51%,32%)]">
                  20g
                </td>
              </tr>
              <tr class="border-b-2">
                <td class="px-10 py-2">
                  Fat
                </td>
                <td class="px-10 py-2 font-[600] text-[hsl(332,51%,32%)]">
                  22g
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>
