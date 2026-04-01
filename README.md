# Kitchen Optimizer

Final project for the Building AI course

## Summary

Kitchen Optimizer is an AI-based idea for organizing food items in a school kitchen storage in the most space-efficient way possible. It takes into account the size, category, and storage needs of food items as well as the shelf’s physical constraints. It can be adapted for other space relevant purposes.

## Background

School kitchens often need to store many different food items in limited space. Some products are large, some are small, and some should be grouped together for practical reasons such as access, freshness, or hygiene.

My motivation for this project is to explore how AI can help turn a cluttered storage shelf into a more organized and efficient system.

This project could help with:

- reducing wasted shelf space
- making food easier to find and access
- improving organization in school kitchens
- supporting practical storage decisions under space constraints

## How is it used?

The user enters information about the food items and the shelf, such as category, size, and storage space. The AI then suggests different shelf arrangements and the user can rate them until a good solution is found.

The solution is intended for people who manage school kitchen storage, such as teachers, kitchen staff, or students responsible for organizing supplies.

## Data sources and AI methods

The project depends on local data, not big data. The relevant data includes:

- a list of food items with category, name, and physical size
- the shelf dimensions and configuration
- possible storage rules or preferences

Possible AI methods for this project include:

- simulated annealing
- genetic algorithms
- rule-based optimization
- user feedback to adjust preferences by creating malus and bonus

## Challenges

This project does not solve every storage problem. It does not automatically understand food safety rules, expiration dates, or special storage needs unless those are added manually.

Another limitation is that entering all food and shelf data can be time-consuming. The model may also miss creative human solutions that are not included in the algorithm.

## What next?

The project could grow into a prototype that:

1. models shelf space more precisely,
2. includes food safety rules,
3. learns user preferences over time,
4. and visualizes shelf arrangements in a simple interface.

## Acknowledgments
Final project for the Building AI course of Linköping University
