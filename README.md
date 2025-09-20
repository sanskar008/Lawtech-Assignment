# LawTech Assignment - Front-End Template Solutions

## Assignment Overview

This project demonstrates my ability to work with pre-designed front-end templates while solving mathematical problems. I was given two specialized templates and had to implement solutions without breaking the original design or structure. It was quite challenging to work within these constraints, but I found creative ways to adapt the content while preserving everything that made the templates work.

## Assignment Requirements

I had to work with two different templates:

- **Template 1**: Trigonometry with Pythagorean Triplet layout (designed for linear steps and arithmetic breakdown)
- **Template 2**: Compound Interest layout (built for problems involving powers, repeated multiplication, and interest-based growth)

The constraints were pretty strict:

- Only modify content inside existing divs (no structural changes)
- Maintain original CSS and structure completely
- Keep arrows, fractions, and highlight boxes consistent with the design
- Reuse existing box types (number boxes, variable boxes, fraction boxes)
- Absolutely no adding/removing divs or altering the layout

## Project Structure

```
Lawtech Assignment/
├── README.md (this file)
├── Original Templates
│   ├── temp1.html (Trigonometry Template)
│   ├── interestcompounded.html (Compound Interest Template)
│   ├── arrow.png
│   └── interesticon.png
├── Template 1 Solutions (Trigonometry)
│   ├── problem1_trigonometry_pythagorean.html
│   └── problem2_trigonometry_verification.html
└── Template 2 Solutions (Compound Interest)
    ├── problem3_compound_interest_rate.html
    └── problem4_compound_interest_calculation.html
```

## Problems Solved

### Template 1 Solutions (Trigonometry)

#### Problem 1: Find Hypotenuse and Trigonometric Ratios

**File**: `problem1_trigonometry_pythagorean.html`

**Problem**: Find the hypotenuse of a right triangle with sides 9 cm and 12 cm, then calculate sin A and cos A.

**How I solved it**:
I started with the Pythagorean theorem since we have two sides of a right triangle. Applied AC² = AB² + BC² and calculated AC² = 9² + 12² = 81 + 144 = 225, which gives us AC = √225 = 15 cm for the hypotenuse.

For the trigonometric ratios, I used the definitions:

- Sin A = opposite/hypotenuse = 12/15 = 4/5
- Cos A = adjacent/hypotenuse = 9/15 = 3/5

**What I changed in the template**:
I updated the triangle dimensions to show 9, 12, and 15 cm, modified the calculation steps to demonstrate the Pythagorean theorem clearly, and adjusted the trigonometric ratio calculations. The original color scheme and layout structure stayed exactly the same.

---

#### Problem 2: Verify Right Triangle and Find All Ratios

**File**: `problem2_trigonometry_verification.html`

**Problem**: Given a triangle with sides 8, 15, 17 cm, verify it's a right triangle and find all trigonometric ratios for angle A.

**How I solved it**:
First, I needed to verify if this is actually a right triangle. I checked using the Pythagorean theorem: 17² = 8² + 15² → 289 = 64 + 225 = 289. Since both sides equal 289, it confirms this is indeed a right triangle and (8, 15, 17) is a Pythagorean triplet.

Then I calculated all the trigonometric ratios for angle A:

- Sin A = opposite/hypotenuse = 15/17
- Cos A = adjacent/hypotenuse = 8/17
- Tan A = opposite/adjacent = 15/8

**What I changed in the template**:
I updated the verification calculations to show the Pythagorean theorem check, modified the triangle labels to display 8, 15, and 17, and added displays for multiple trigonometric ratios. The original formula boxes and highlighting system remained unchanged.

---

### Template 2 Solutions (Compound Interest)

#### Problem 3: Find Rate of Compound Interest

**File**: `problem3_compound_interest_rate.html`

**Problem**: A sum of ₹8000 amounts to ₹10,648 in 3 years at compound interest. Find the rate of interest.

**How I solved it**:
I used the compound interest formula A = P(1 + r/100)ⁿ and set up the equation: 10648 = 8000(1 + r/100)³.

After simplifying, I got (1 + r/100)³ = 10648/8000 = 1331/1000. This is where it got interesting - I recognized that 1331 = 11³ and 1000 = 10³, so I could take the cube root of both sides to get (1 + r/100) = 11/10.

Solving for r: r = (11/10 - 1) × 100 = 1/10 × 100 = 10%

**What I changed in the template**:
I updated all the values to match the problem - principal (₹8000), amount (₹10,648), and time (3 years). I modified the fraction calculations to clearly show how 1331/1000 equals 11³/10³, adjusted the final rate calculation to show 10%, and even added a verification calculation for what the amount would be after 2 years.

---

#### Problem 4: Calculate Compound Interest Amount

**File**: `problem4_compound_interest_calculation.html`

**Problem**: Calculate the compound interest on ₹15,000 for 2 years at 8% per annum compounded annually.

**How I solved it**:
This was a straightforward application of the compound interest formula A = P(1 + r/100)ⁿ. I plugged in the values: A = 15000(1 + 8/100)², which becomes A = 15000(1.08)².

Calculating (1.08)² = 1.1664, so A = 15000 × 1.1664 = ₹17,496.

The compound interest is simply the difference: CI = 17496 - 15000 = ₹2,496.

**What I changed in the template**:
I updated all the values to match this problem - principal (₹15,000), rate (8%), and time (2 years). I modified the calculation steps to show both decimal and fraction conversions clearly, added the final compound interest calculation, and made sure the original flow and arrow structure remained intact.

## Design Consistency Maintained

### Visual Elements I Preserved

**Color-Coded Elements**: I kept all the gradient backgrounds using the original num0-num9 classes for number boxes, maintained the original varbox styling for variables, and preserved the green highlighting (#1bad83) for final answers. The formula tables kept their black background with white text, and all arrows and flow indicators stayed exactly as designed.

**Layout Structure**: For Template 1, I preserved the triangle diagrams, dimension labels, and formula boxes exactly as they were. For Template 2, the multi-column layout, dashed containers, and arrow sequences remained unchanged. All the box shadows that give the 3D effects stayed consistent, and the typography (Calibri font family, bold weights, proper sizing) was untouched.

## Technical Implementation

### Code Quality

I made sure to maintain proper HTML5 semantic structure with correct document structure and meta tags. The CSS remained completely untouched - no modifications to any styling rules. All the responsive elements kept their flexible layouts and proper spacing, and the visual hierarchy that emphasizes important information stayed intact.

### Mathematical Accuracy

I double-checked all my work to ensure accuracy. The Pythagorean theorem applications and verifications are correct, all trigonometric ratio calculations (sine, cosine, tangent) are accurate, the compound interest formula applications and rate calculations are proper, and any fraction simplifications follow correct mathematical rules.

### User Experience

The solutions follow a clear visual flow with logical progression through each step. Important answers are highlighted appropriately, and each solution has educational value by showing step-by-step mathematical reasoning. The overall appearance remains clean and organized, just like the original templates.

## Assignment Success Summary

| Requirement             | Status   | What I Accomplished                             |
| ----------------------- | -------- | ----------------------------------------------- |
| Template 1 Problems (2) | Complete | Pythagorean theorem & trigonometry verification |
| Template 2 Problems (2) | Complete | Rate finding & compound interest calculation    |
| Structure Preservation  | Complete | Zero layout modifications                       |
| CSS Integrity           | Complete | No styling changes                              |
| Mathematical Accuracy   | Complete | All calculations verified                       |
| Visual Consistency      | Complete | Original design maintained                      |

## What I Learned and Accomplished

Working on this assignment taught me a lot about precision and constraint-based development. I successfully solved 4 complex mathematical problems without breaking any template constraints, which required careful planning and creative thinking.

The mathematical aspect was really interesting - implementing accurate calculations with proper notation while working within the visual constraints of the templates. I'm particularly proud of how I maintained the professional appearance of both templates while completely changing the content to match different problems.

Creating step-by-step solutions that are educational and easy to follow was important to me. I wanted anyone looking at these solutions to understand not just the answer, but the process. The code itself remains clean and well-structured with the CSS integrity completely preserved.

## Why This Project Matters

This assignment demonstrates several important skills that I think are valuable in web development:

**Technical Precision**: Working within strict constraints while still achieving complex goals requires careful attention to detail and creative problem-solving.

**Mathematical Competency**: Understanding trigonometry and compound interest concepts well enough to implement them clearly shows analytical thinking skills.

**Attention to Detail**: Preserving design elements while completely changing content requires careful observation and systematic approach.

**Problem-Solving**: Adapting templates for different mathematical contexts while keeping them functional and visually consistent.

**Professional Standards**: Creating deliverables that are production-ready and maintain the original quality standards.

## Viewing the Results

To see the solutions in action:

1. Open any HTML file in a web browser
2. Make sure `arrow.png` and `interesticon.png` are in the same directory
3. You'll see the mathematical solutions presented with the original template styling intact

---

**Developed by**: Sanskar  
**Assignment**: LawTech Front-End Template Solutions  
**Purpose**: Internship application demonstrating technical precision and mathematical competency

This project reflects my approach to development - careful attention to requirements, respect for existing design decisions, and the ability to deliver quality work within constraints. I hope it demonstrates the kind of thoughtful, precise work I'd bring to the team.
