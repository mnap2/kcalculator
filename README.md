# kcalculator - calorie tracking app
kcalculator is a calorie tracking mobile app I’m building to match my very specific personal workflow. Existing calorie trackers didn’t support my custom calorie calculating algorithm and all of its nuances. That's why I previously used a notes app plus a calculator, but that quickly became tedious and has always caused me to stop tracking after no more than two weeks. So now, I'm making this app to make calorie tracking more doable for me.
## Planned features:
- Add and edit meal entries for any day
  - Add and edit ingredients for each meal entry
    - Store a calorie value for each ingredient (optionally include weight in grams or volume in milliliters)
    - Save frequently used ingredients for quick reuse
  - Calculate a meal’s total calories
    - Split a meal into portions and count only the calories for your portion
      - Mark specific ingredients as not split (for example, if people ate different numbers of bread slices, you can enter only the number of slices you ate and not split those calories) 
  - Sum total calorie intake per day
- Save reusable meal templates
  - Choose a template when adding a new meal entry
    - Scale the whole meal size (multiply calories by a factor to make the meal larger or smaller)
    - Edit individual ingredient properties for the current meal