General Healthy-Adult Dietary Guidelines

These are general reference guidelines for a healthy adult with normal kidney and metabolic function. They are not medical advice and are meant only as a baseline for everyday diet coaching conversations in this repository.

Balance and variety. Aim for a plate that includes vegetables and fruit, whole grains, a source of protein (meat, fish, eggs, dairy, legumes, or tofu), and healthy fats at most meals.

Protein. Around 0.8 to 1.2 grams of protein per kilogram of body weight per day is a reasonable range for a healthy adult, spread across meals.

Sodium. Try to stay under about 2,300 mg of sodium per day. Watch out for processed foods, instant noodles, packaged lunch boxes, and salty snacks, which are common sources of excess sodium.

Sugar and refined carbohydrates. Limit sugary drinks, desserts, and refined starches. Prefer whole grains such as brown rice or oats over refined white rice or white bread when possible.

Fats. Favor unsaturated fats such as olive oil, nuts, and fish, and limit fried food and foods high in saturated or trans fat.

Hydration. Water is the best everyday beverage. Limit sugary drinks and moderate caffeine and alcohol intake.

Fiber. Include vegetables, fruit, legumes, and whole grains regularly to support digestion and overall health.

Portion size and eating pattern. Eat regular meals, avoid very large portions late at night, and pay attention to overall calorie intake relative to activity level.

User baseline

This diet log is for a healthy adult aged 30-35 with normal kidney, metabolic, and general health check-up results (no diagnosed chronic conditions). Coaching should stay at a general prevention level, not clinical management.

Physical stats: height 167cm, weight 65kg. Activity level: light activity (occasional walking, light housework).

General chronic-disease prevention notes (kidney disease, diabetes, and other common conditions in Taiwan)

For this age/health baseline, coaching should additionally emphasize:
- Prioritize whole-food protein sources (fish, eggs, tofu/legumes, lean meat) over processed/cured meats.
- Minimize sodium from soup bases, dipping sauces, and instant/processed foods, a recurring theme given how common these are in daily meals.
- Limit sugary drinks and refined starches; prefer whole grains.
- Include a vegetable serving at most meals for fiber and micronutrient variety.
- Favor unsaturated fats; limit fried food.
- Encourage adequate hydration, especially after higher-sodium meals.
- Encourage regular checkups (blood sugar, blood pressure, kidney function) as part of long-term prevention; this is general wellness advice, not a substitute for medical screening.

This remains general wellness guidance for prevention purposes. If the user is later diagnosed with a condition, put on medication, or receives abnormal lab results, that changes the baseline; pause general advice and suggest consulting a healthcare professional for individualized guidance.

Notes for the assistant

When the user logs a meal, compare it qualitatively against these guidelines (for example: sodium looks high, protein looks adequate, could use more vegetables) rather than giving precise clinical targets. If the user mentions any new medical condition, medication, or lab result, treat that as new information to discuss, and suggest they follow up with a healthcare professional rather than relying solely on this file.

User preference: proactive sodium coaching (confirmed with user via explicit question, 2026-08-26)
The user explicitly said they don't want purely passive/neutral logging on sodium — they want the assistant to actively help them reduce high-sodium choices, not just note "sodium is a bit high, drink more water" every time.

Going forward, when a logged meal (or a run of several meals/days) is high in sodium:
- Don't just flag it and recommend extra water as the main response. Water is still fine to mention (per the hydration section above), but it should not be the primary or only piece of advice for a high-sodium meal.
- Proactively suggest a concrete, realistic swap or modification for that specific food/context — e.g., for lu-wei (滷味) suggest eating the items but not drinking the broth, for noodle soups suggest asking for less salt/oil or leaving some broth, for instant soups suggest a lower-sodium variant or smaller garnish portion, for braised-sauce rice dishes suggest less sauce. Tailor the suggestion to what was actually eaten rather than giving a generic tip.
- If sodium has been flagged as high across multiple consecutive meals or days, say so directly (e.g., "the last few meals have all run high in sodium") and suggest a specific next meal or swap to bring it back down, rather than treating each meal as an isolated event.
- This is still general wellness coaching, not clinical sodium restriction — keep the tone warm and practical, but be willing to give a concrete "maybe skip/reduce X" recommendation rather than staying purely descriptive.

User preference: water intake recommendation (PER-MEAL amount, confirmed format v4)
This format has been revised multiple times based on user feedback. History, for context (do not reintroduce earlier versions):
  v1: incremental "+XXXml" shown alone per meal -> user thought that was the whole day's target (too low). Rejected.
  v2: cumulative running full-day total shown per meal -> user didn't want a daily running total in the per-meal row. Rejected.
  v3: fixed standalone per-meal baseline (300-500ml, same for every meal, unrelated to daily total) + that meal's situational adjustment -> user initially confirmed this, but then said the three meals' baselines SHOULD sum to the daily target, which v3 does not do. Rejected/superseded.
  v4 (CURRENT, confirmed with user via explicit question): the daily baseline (2100-2300ml/day) is split evenly across 3 meals (~700-770ml each), and then that meal's own situational adjustment is added on top. With this version, the three meals' baseline portions DO sum to the full daily baseline by design.

Format (table row, last row of the meal table):
| 💧 這餐建議飲水 | XXX-XXXml(每餐基礎700-770ml + 這餐特殊因素:原因與加量) | — |

Per-meal calculation (v4, current):
1. Per-meal baseline = daily baseline (2100-2300ml) ÷ 3 meals ≈ 700-770ml per meal. This is the same for breakfast, lunch, and dinner (even split; snacks between meals do not get their own share of this baseline — only the 3 main meals do).
2. Add this meal's own situational adjustment(s), only for factors that apply to THIS specific meal/drink:
   - High sodium in this meal: +300-500ml
   - Caffeine or alcohol in this meal/drink: +100-200ml per serving
   - Hot weather / noticeable sweating around this meal: +300-500ml
   - Moderate-to-high intensity exercise around this meal: +350-500ml per 30 minutes
3. Result = per-meal baseline (700-770ml) + applicable situational adjustment(s) for that meal only. Example: a high-sodium lunch = 700-770ml baseline + 300-500ml sodium adjustment = 1000-1270ml recommended for that lunch.
4. Do NOT accumulate previous meals' adjustments into this number — each meal's water row is self-contained (its own 1/3 baseline share + its own situational adjustments only), not a running total across the day.
5. Because the per-meal baseline is now an even 3-way split of the daily total, the three meals' baseline portions (700-770ml x 3 ≈ 2100-2300ml) do sum to the daily baseline. Situational adjustments (sodium, caffeine, heat, exercise) are on top of that and are meal-specific extras, not part of the baseline split.
6. If the user asks for their full-day water target directly, answer using the daily baseline + activity level formula below (which is the same 2100-2300ml figure the per-meal baselines are split from) — optionally also mention that situational adjustments from meals/snacks add further on top of that daily figure.
7. This should be a standing habit for every response involving food (whether logging a meal already eaten, or advising on what to eat/order next), not something the user needs to ask for each time.
8. Note (added 2026-08-26): on days where most/all meals trigger the sodium adjustment, the daily total can regularly exceed ~3000ml. This is not dangerous for a healthy adult with normal kidney function, but it is a signal of a genuinely high-sodium day/pattern. Per the "proactive sodium coaching" preference above, respond to that pattern by suggesting concrete lower-sodium swaps for upcoming meals, not just by continuing to recommend more water.

Daily water target formula (source for the 700-770ml/meal split above; also usable directly if the user asks about their full-day total)
1. Baseline: body weight (kg) x 30-35ml/day.
   - User weight: 65kg -> baseline range 1950-2275ml/day.
2. Activity level adjustment (added to baseline):
   - Sedentary: +0ml
   - Light activity (occasional walking, light housework): +100-200ml
   - Moderate activity (regular exercise several times/week): +300-500ml
   - High activity (frequent exercise or physically demanding work, frequent sweating): +500-800ml
   - User's current activity level: light activity -> +150ml
   - User's current daily baseline (weight + activity combined): approx. 2100-2300ml/day. Divided evenly across 3 meals: approx. 700-770ml per meal (used as the per-meal baseline above).
3. This is a general wellness estimation method, not a precise medical prescription — actual needs vary by individual (kidney function, cardiovascular status, medications, etc.). If the user's height/weight/activity level changes, or they get diagnosed with a condition, ask them to update this section and treat medical changes per the "User baseline" notes above.
