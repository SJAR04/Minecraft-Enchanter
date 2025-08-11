# Minecraft Enchantment Adviser & Optimal Anvil Order Calculator

A fast, lightweight web tool to calculate the optimal anvil order for enchanting items in Minecraft: Java Edition. Minimize your experience (XP) cost by finding the cheapest sequence of combinations for your gear.

## ✨ Features

-   **Optimal XP Cost:** Finds the cheapest enchantment order to save you valuable experience levels.
-   **Step-by-Step Guide:** Generates a clear, numbered list of anvil combinations to follow.
-   **Full Game Support:** Includes a comprehensive database of items, enchantments, and their specific costs for Minecraft: Java Edition.
-   **Conflict Resolution:** Automatically handles and prevents incompatible enchantments (e.g., Mending vs. Infinity, Sharpness vs. Smite).
-   **"Too Expensive" Alerts:** Warns you if any step in the process would cost 40+ levels in survival mode.
-   **Version Selection:** Lets you switch between modern (1.20+) and legacy anvil mechanics.
-   **Shareable Links:** Creates a custom URL for your specific build, making it easy to share your enchantment plans.
-   **Modern UI:** Responsive design with automatic light/dark mode and local storage to save your selections.

## 🚀 How to Use

1.  Open `index.html` in any web browser.
2.  Select the item you want to enchant (e.g., Diamond Sword).
3.  Check the boxes for your desired enchantments and set their levels.
4.  Click **"Calculate Optimal Order"**.
5.  Follow the generated step-by-step results to build your perfect item for the lowest XP cost.

## 🛠️ How It Works

The calculator uses a **recursive algorithm with memoization** (dynamic programming) to efficiently explore all possible combination sequences. It accurately models the official Minecraft: Java Edition anvil mechanics, including:

-   **Prior Work Penalty:** The increasing cost of working on an item multiple times.
-   **Enchantment Costs:** The specific XP cost multiplier for each enchantment.
-   **Combining Rules:** The logic for merging and upgrading enchantments.

By evaluating every path, it guarantees the true optimal solution with the lowest total XP cost.

## 💻 Technology Stack

-   **HTML5**
-   **CSS3**
-   **Vanilla JavaScript (ES6+)**

No frameworks, no dependencies. Just a pure, high-performance tool.

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
