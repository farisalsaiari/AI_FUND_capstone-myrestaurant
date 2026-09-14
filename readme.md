# AI Fundamentals in the Workplace – Capstone Project

## Using ChatGPT to Improve Menu Items in Platform01

**Course:** AI Fundamentals in the Workplace  
**Date:** 14/09/2026

---

## 1. Target Task

One recurring text-based task in my restaurant04 management project is reviewing
menu items before publishing them to customers.

Menu items may be entered with:

- Spelling mistakes
- Weak English or Arabic names
- Missing or incorrect categories
- Basic descriptions
- Inconsistent formatting

For this project, I created four fictional draft items in Platform01.

My first item was entered as **“Saudi Coffe”** with the Arabic name
**“قهوه”**, no category and a basic description.

The other items also had messy names, incorrect categories or incomplete
descriptions.

I used ChatGPT to review all four items together and recommend better English
and Arabic names, suitable categories and clearer descriptions.

This task is:

- Real and related to my restaurant04 management project
- Repeated when new menu items are added
- Mainly text-based
- Suitable for AI assistance
- Easy for me to verify before applying the changes

---

## 2. Original Menu Items

The following fictional items were entered into Platform01 before using
ChatGPT:

| No. | Original English Name | Original Arabic Name | Original Category | Price | Original Description |
|---:|---|---|---|---:|---|
| 1 | Saudi Coffe | قهوه | None | SAR 7 | Saudi coffee hot. |
| 2 | Ice Spanich | سبانش بارد | Drinks | SAR 28 | Cold Spanish latte. |
| 3 | Cake Choco | كيك | None | SAR 24 | Chocolate cake. |
| 4 | Black Coffe | قهوه بلاك | Drinks | SAR 8 | Black coffee hot or cold. |

### Screenshot 1: Original Items in Platform01

<img width="1152" height="626" alt="Screenshot 1448-04-03 at 9 46 16 PM" src="https://github.com/user-attachments/assets/a774028b-eca4-41f8-a2ad-02a60423bac0" />

<img width="1436" height="784" alt="Screenshot 1448-04-03 at 9 46 49 PM" src="https://github.com/user-attachments/assets/274d31a1-5749-42ca-a768-f6a123fe815d" />

This screenshot shows the messy item information before using ChatGPT.


---

## 3. Data Masking and Sanitised Input

Before submitting the information to ChatGPT, I removed all personal,
confidential and identifying information.

### Information Removed or Replaced

| Information Type | Masking Action |
|---|---|
| Platform name | Replaced with “Platform01” |
| Restaurant name | Replaced with “Restaurant04” |
| Owner's name | Removed |
| Employee names | Removed |
| Customer information | Removed |
| Telephone numbers | Removed |
| Email addresses | Removed |
| Account identifiers | Removed |
| Branch address | Removed |
| Confidential organisational information | Not included |

The four menu items were fictional demonstration items. They did not contain
real merchant, employee or customer information.

The browser address and any account information were hidden or cropped in the
screenshots.

---

## 4. Structured R.A.C.E. Prompt

I structured my prompt using all four pillars of the R.A.C.E. framework:
Role, Action, Context and Expectation.

### Role

You are a professional bilingual menu optimisation assistant for cafés and
restaurant ordering platforms in Saudi Arabia.

### Action

Review and improve four messy draft menu items. Correct their English names,
provide natural Arabic names, assign appropriate categories and improve their
descriptions.

### Context

The items are fictional examples entered into a restaurant management
platform. They contain spelling mistakes, unclear Arabic names, missing or
incorrect categories and weak descriptions.

The prices must remain unchanged because ingredient costs, serving sizes,
competitor prices and target profit margins are unavailable.

### Expectation

Return the result in a structured Markdown table. Use professional English and
natural Arabic suitable for customers in Saudi Arabia.

Do not invent ingredients, sizes, flavours or preparation methods. Keep the
existing prices unchanged and identify information that requires verification.

### Complete Prompt Submitted to ChatGPT

> **Role:**
>
> You are a professional bilingual menu optimisation assistant for cafés and
> restaurant ordering platforms in Saudi Arabia. 
>
> **Action:**
>
> Review and improve the four messy draft menu items provided below.
>
> For each item:
>
> 1. Correct and improve the English product name.
> 2. Provide a natural Arabic product name suitable for Saudi customers.
> 3. Assign the appropriate menu category or categories.
> 4. Improve the English product description.
> 5. Provide a matching natural Arabic description.
> 6. Retain and display the existing price.
> 7. Identify any information that should be verified.
>
> Standardise the spelling, naming, categories and description style across
> the menu.
>
> **Context:**
>
> I am preparing a small demonstration menu for restaurant04 inside a Platform01.
> The draft items contain spelling mistakes, unclear Arabic names,
> missing or incorrect categories and weak descriptions.
>
> The intended final products and categories are:
>
> - Saudi Coffee belongs to the Hot Coffee category.
> - Iced Spanish Latte belongs to the Cold Coffee category.
> - Chocolate Cake belongs to the Desserts category.
> - Black Coffee is available hot or cold and belongs to both the Hot Coffee
>   and Cold Coffee categories.
>
> The existing prices must remain unchanged because ingredient costs, serving
> sizes, competitor prices and target profit margins have not been provided.
>
> The Arabic names and descriptions should sound natural to customers in Saudi
> Arabia. They should not be awkward literal translations.
>
> All information is fictional and sanitised. It contains no real customer
> names, employee names, telephone numbers, email addresses, account
> identifiers or confidential organisational information.
>
> **Expectation:**
>
> Return the result as a Markdown table with these columns:
>
> - Original Name
> - Recommended English Name
> - Recommended Arabic Name
> - Recommended Category or Categories
> - Current Price
> - Improved English Description
> - Improved Arabic Description
> - Verification Note
>
> Follow these rules:
>
> - Correct all spelling mistakes.
> - Use “Saudi Coffee” and “قهوة سعودية” for the first item.
> - Assign the first item to “Hot Coffee.”
> - Use “Iced Spanish Latte” and “سبانش لاتيه بارد” for the second item.
> - Assign the second item to “Cold Coffee.”
> - Use “Chocolate Cake” and “كيكة الشوكولاتة” for the third item.
> - Assign the third item to “Desserts.”
> - Use “Black Coffee” and “قهوة سوداء” for the fourth item.
> - Assign the fourth item to both “Hot Coffee” and “Cold Coffee.”
> - Keep each English and Arabic description under 20 words.
> - Use clear, natural Arabic appropriate for a Saudi café menu.
> - Do not invent ingredients, sizes, flavours or preparation methods.
> - Keep all existing prices unchanged.
> - Do not claim that the prices are correct without supporting cost data.
> - Use only the supplied information.
> - State that pricing requires cost and size verification.
>
> **Draft menu items:**
>
> **Item 1**
>
> Original English name: Saudi Coffe  
> Original Arabic name: قهوه  
> Current category: None  
> Price: SAR 7  
> Original description: Saudi coffee hot.
>
> **Item 2**
>
> Original English name: Ice Spanich  
> Original Arabic name: سبانش بارد  
> Current category: Drinks  
> Price: SAR 28  
> Original description: Cold Spanish latte.
>
> **Item 3**
>
> Original English name: Cake Choco  
> Original Arabic name: كيك  
> Current category: None  
> Price: SAR 24  
> Original description: Chocolate cake.
>
> **Item 4**
>
> Original English name: Black Coffe  
> Original Arabic name: قهوه بلاك  
> Current category: Drinks  
> Price: SAR 8  
> Original description: Black coffee hot or cold.



---

## 5. Initial ChatGPT Output

ChatGPT returned corrected English and Arabic names, suitable categories and
improved descriptions.

| Original Name | Recommended English Name | Recommended Arabic Name | Category | Price | Improved English Description | Improved Arabic Description |
|---|---|---|---|---:|---|---|
| Saudi Coffe | Saudi Coffee | قهوة سعودية | Hot Coffee | SAR 7 | Traditional Saudi coffee served hot. | قهوة سعودية تقليدية تقدم ساخنة. |
| Ice Spanich | Iced Spanish Latte | سبانش لاتيه بارد | Cold Coffee | SAR 28 | A cold Spanish latte served as a chilled coffee drink. | سبانش لاتيه بارد يقدم كمشروب قهوة بارد. |
| Cake Choco | Chocolate Cake | كيكة الشوكولاتة | Desserts | SAR 24 | A chocolate cake served as a dessert. | كيكة شوكولاتة تقدم كحلى. |
| Black Coffe | Black Coffee | قهوة سوداء | Hot Coffee and Cold Coffee | SAR 8 | Black coffee available hot or cold. | قهوة سوداء متوفرة ساخنة أو باردة. |

ChatGPT retained the four original prices. It also warned that the prices
required cost and serving-size verification.

### Screenshot 3: Initial ChatGPT Output

<img width="1169" height="803" alt="Screenshot 1448-04-03 at 9 47 26 PM" src="https://github.com/user-attachments/assets/68bd7a19-bc82-47f2-befb-966b908d4594" />

This screenshot shows ChatGPT's first response.

---

## 6. Iterative Refinement

The initial response was useful, but some descriptions were longer than
necessary and repeated information.

For example, the Iced Spanish Latte description repeated the word “cold” and
the phrase “chilled coffee drink.” I wanted the descriptions to be shorter
and more suitable for a digital menu.

I sent a follow-up prompt to improve the existing response rather than
restarting the task.

### Follow-Up Prompt

> The names, categories and prices are correct, but refine the descriptions.
>
> Make every English and Arabic description shorter and easier to read on a
> digital menu.
>
> Remove repeated words and unnecessary phrases. Do not invent ingredients,
> sizes, flavours or preparation methods.
>
> Keep all names, Arabic names, categories and prices unchanged.
>
> Keep every description under 12 words and return the final result as a
> compact Markdown table.

### Refined ChatGPT Output

| English Name | Arabic Name | Category | Price | Final English Description | Final Arabic Description |
|---|---|---|---:|---|---|
| Saudi Coffee | قهوة سعودية | Hot Coffee | SAR 7 | Traditional Saudi coffee served hot. | قهوة سعودية تقليدية تقدم ساخنة. |
| Iced Spanish Latte | سبانش لاتيه بارد | Cold Coffee | SAR 28 | Spanish latte served cold. | سبانش لاتيه يقدم بارداً. |
| Chocolate Cake | كيكة الشوكولاتة | Desserts | SAR 24 | Chocolate cake served as a dessert. | كيكة شوكولاتة تقدم كحلى. |
| Black Coffee | قهوة سوداء | Hot Coffee and Cold Coffee | SAR 8 | Black coffee available hot or cold. | قهوة سوداء متوفرة ساخنة أو باردة. |

### Screenshot 4: Follow-Up Prompt and Refined Output

<img width="1151" height="675" alt="Screenshot 1448-04-03 at 9 53 21 PM" src="https://github.com/user-attachments/assets/6ce9cd8d-6772-4012-bff4-886a6c99a430" />

<img width="1430" height="793" alt="Screenshot 1448-04-03 at 9 52 47 PM" src="https://github.com/user-attachments/assets/7f977019-98bd-4306-b156-d42cf7739928" />

This screenshot shows the follow-up prompt and the improved response.


---

## 7. Applying the Result in Platform01

After reviewing the refined output, I updated the four demonstration items in
Platform01.

The applied values were:

| Final English Name | Final Arabic Name | Final Category | Price |
|---|---|---|---:|
| Saudi Coffee | قهوة سعودية | Hot Coffee | SAR 7 |
| Iced Spanish Latte | سبانش لاتيه بارد | Cold Coffee | SAR 28 |
| Chocolate Cake | كيكة الشوكولاتة | Desserts | SAR 24 |
| Black Coffee | قهوة سوداء | Hot Coffee and Cold Coffee | SAR 8 |


---

## 8. Verification and Accuracy

I manually compared the ChatGPT output with the original sanitised input and
the updated Platform01 items.

I verified that:

- “Saudi Coffe” was corrected to “Saudi Coffee.”
- “Ice Spanich” was corrected to “Iced Spanish Latte.”
- “Cake Choco” was corrected to “Chocolate Cake.”
- “Black Coffe” was corrected to “Black Coffee.”
- Natural Arabic names were provided for all four items.
- Saudi Coffee was assigned to Hot Coffee.
- Iced Spanish Latte was assigned to Cold Coffee.
- Chocolate Cake was assigned to Desserts.
- Black Coffee was assigned to Hot Coffee and Cold Coffee.
- All four original prices remained unchanged.
- No ingredients, sizes or flavours were invented.
- No private or confidential information appeared in the prompt or output.

### Arithmetic Verification

I checked the prices before and after applying the recommendations.

Original total:

**SAR 7 + SAR 28 + SAR 24 + SAR 8**

Updated total:

**SAR 7 + SAR 18 + SAR 19 + SAR 8**

The total did not change, confirming that ChatGPT preserved all four entered
prices.

The prices were not treated as verified selling-price recommendations because
ingredient costs, serving sizes and profit-margin information were unavailable.

---

## 9. Impact and Estimated Time Saved

I compared the estimated time needed to review and rewrite the four items
manually with the time needed using ChatGPT.

| Method | Estimated Time |
|---|---:|
| Manual review and bilingual rewriting | 35 minutes |
| Using ChatGPT and manually verifying the output | 12 minutes |
| Estimated time saved | 23 minutes |

### Time-Saving Calculation

**35 minutes − 12 minutes = 23 minutes saved**

Estimated percentage reduction:

**23 ÷ 35 × 100 = 65.7%**

Using ChatGPT reduced the estimated completion time by approximately **66%**.

Human verification was still required before updating Platform01, especially
for the Arabic wording, categories and prices.

---

## Conclusion

ChatGPT helped me transform four messy menu items into clearer and more
consistent bilingual menu entries.

The R.A.C.E. framework allowed me to define the role, required actions,
business context and expected output. The follow-up prompt improved the
descriptions without restarting the task.

Data masking protected personal and organisational information. Manual
verification ensured that the names, categories, descriptions and prices were
correct before I applied the changes inside Platform01. 


------


### 🔗 Training Program

This project was completed as part of the L0-FAE — AI Fundamentals for the Workplace training program at SDAIA Academy, under the supervision of Abdullah Khalid AlShahrani.

The portfolio demonstrates the practical application of AI fundamentals in the workplace through prompt engineering, professional writing, information processing, verification and fact-checking, safe and responsible use, and daily task integration.

Official SDAIA Academy GitHub:  
https://github.com/SDAIAAcademy 
