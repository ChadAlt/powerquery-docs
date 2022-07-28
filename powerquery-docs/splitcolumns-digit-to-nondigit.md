---
title: Split columns by digit to non-digit
description: Split columns by digit to non-digit
author: jessli20

ms.topic: conceptual

ms.date: 06/04/2020
ms.author: bezhan
---

# Split columns by digit to non-digit

In Power Query, you can split a column through different methods.
In this case, the column(s) selected can be split by every instance of a digit followed by a non-digit.

## Where to find Split columns > By Digit to Non-Digit

You can find the **Split Columns: By Digit to Non-Digit** option in three places:

* **Home tab**&mdash;under the **Split Column** dropdown menu inside the **Transform** group.

   ![Image shows By Digit to Non-Digit under the Home tab.](images/sc-home-dtnd.png)

* **Transform tab**&mdash;under the **Split Column** dropdown menu inside the **Text Column** group.

   ![Image shows By Digit to Non-Digit under the Transform tab.](images/sc-transform-dtnd.png)

* **Right-click a column**&mdash;inside the **Split Column** option.

   ![Image shows By Digit to Non-Digit when right-clicking a column.](images/sc-rightclick-dtnd.png)

## Split columns by digit to non-digit into columns

The initial table in this example will be the one shown in the image below, with a column for **Pets** and other extra columns.
This example will only focus on the **Pets** column.

![Image showing table with Pets and Age columns, with four rows, with the Pets column containing the rank of the animal.](images/sc-before-dtnd.png)

This column holds two values in each row:

* **Rank**&mdash;The rank of the animal.
* **AnimalType**&mdash;The second part of the word is the type of animal.

In this example, you want to split this column into the two columns described in the list above. Select the column and then select the option to split the column by digit to non-digit.

This single column will split into multiple columns, given every instance of a digit followed with a non-digit. In this case, it only splits it into two.

Your final table will look like the following image.

![Image showing Pets.1, Pets.2 and Age columns, with the rank and type of pet separated into the two columns.](images/sc-after-dtnd.png)

