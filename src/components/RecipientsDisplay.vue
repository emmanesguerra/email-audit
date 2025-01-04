<script setup lang="ts"></script>

<template></template>

<!--
TASKS

Recipients 
Simplified
1. First recipient record must be displayed.
   IF recipient > 1, replace the succeeding to `, ...` and show badge
   IF recipient = 1 allowed it to be clipped with ...
2. This functionality should work on any screen size and when the screen is resized.
3. For the element that holds the list of recipients, the `display` must be set to `flex` and the `align-items` property must be set to `center` to ensure alignment correctness.
4. Do not add new/extra functionalities and features.

Full
1. If all the email addresses in the recipients list fit in the available space, 
   display them as they are, delimited by a comma and space 
   (e.g. `John.Smith@gmail.com, Jane.Smith@outlook.com`)
2. If there is not enough space to display the entire recipients list, it must be trimmed. 
   To prevent showing clipped email addresses that are hard to read, show only the portion of the recipients list that does fit. 
   In other words, if the entirety of an email address does not fit, it must not be shown.
3. If the recipients list has been trimmed (i.e. at least one email address is not shown), add `, ...` after the last email address shown. 
   Furthermore, the rightmost end of the column must indicate the number of trimmed recipients with the provided `RecipientsBadge` component.
4. A special case is given to the first recipient. 
   If there is not enough space to fit even the first recipient's email address, the email address is allowed to be clipped with an ellipsis. 
   If there is only one recipient, a badge must not be shown. If there is more than one recipient, the first recipient must be excluded from the number of trimmed recipients in the badge.
5. This functionality should work on any screen size and when the screen is resized. 
   For simplicity, this will only be tested in a recent version of a `Chromium` browser.
6. For the element that holds the list of recipients, the `display` must be set to `flex` and the `align-items` property must be set to `center` to ensure alignment correctness.
7. Do not modify or add new props to the `RecipientsBadge` component.
8. Do not re-order the recipients.
9. Do not add new/extra functionalities and features.

Tooltips
Simplified
1. The recipients list must be shown in a tooltip at the **top right** corner of the viewport.
2. The tooltip must only be shown when the user hovers over a `RecipientsBadge` component.
3. The tooltip must display **`all of the email addresses in the recipients list, delimited by a comma and space`** (e.g. `John.Smith@gmail.com, Jane.Smith@outlook.com`).
4. Assume that the viewport is wide enough to show the tooltip without any truncation.
5. Do not create a new file, the tooltip must be located inside the `RecipientsDisplay` file.
6. The tooltip should have the following styles:
    a. Margin from the top right corner of the viewport is `8px`.
    b. Padding top and bottom are `8px`.
    c. Padding left and right are `16px`.
    d. Background color is `#666`.
    e. Text color is `#f0f0f0`.
    f. Border radius is `24px`.
    g. The `display` property must be set to `flex` and the `align-items` property must be set to `center` to ensure alignment correctness.

Full
1. The recipients list must be shown in a tooltip at the **top right** corner of the viewport.
2. The tooltip must only be shown when the user hovers over a `RecipientsBadge` component.
3. The tooltip must not be shown if the user is not hovering over a badge.
4. The tooltip must display **`all of the email addresses in the recipients list, delimited by a comma and space`** (e.g. `John.Smith@gmail.com, Jane.Smith@outlook.com`).
5. Assume that the viewport is wide enough to show the tooltip without any truncation.
6. Do not create a new file, the tooltip must be located inside the `RecipientsDisplay` file.
7. Do not re-order the recipients, display them as they are.
8. Do not add new/extra functionalities and features.
9. The tooltip should have the following styles:
    a. Margin from the top right corner of the viewport is `8px`.
    b. Padding top and bottom are `8px`.
    c. Padding left and right are `16px`.
    d. Background color is `#666`.
    e. Text color is `#f0f0f0`.
    f. Border radius is `24px`.
    g. The `display` property must be set to `flex` and the `align-items` property must be set to `center` to ensure alignment correctness.
-->