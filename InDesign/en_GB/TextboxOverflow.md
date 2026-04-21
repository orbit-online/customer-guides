# Automatic creation of pages as needed

[⟵](../README.md)

## Copy the text box to `A-Master`

![Copy text box to A-Master](../assets/TextboxOverflow/01-copy-textbox-to-a-master.gif)

1. Select the text box whose content you want to overflow to the next page.
2. Right-click and choose `Copy`.
3. Double-click `A-Master` in the `Pages` panel to switch to the master spread.
4. Right-click in the middle of the page and choose `Paste in Place`.

## Make the text box a primary text frame (`Primary Textbox`)

![Make textbox primary](../assets/TextboxOverflow/02-make-textbox-primary.gif)

1. Double-click the text box.
2. Select all the text content.
3. Delete the text.
4. Press the `Esc` key to move focus to the text frame.
5. Click the small paper icon so that a small arrow appears.

## Apply the `Master spread` to the page

![Apply master to first page](../assets/TextboxOverflow/03-apply-master-to-spread.gif)

1. Right-click page `1`.
2. Select `Apply Master to Pages`.
3. Verify that `A-Master` is set next to `Apply Master:`.
4. Click `OK`.

## Move the original text box

![Move non-primary textbox away](../assets/TextboxOverflow/05-move-non-primary-textbox-away.gif)

1. Double-click the page we copied the text box from.
2. Click the text box.
3. Move the text box off the page.
4. Verify that the primary text frame from `A-Master` is available on the page.

## Create a new `Master Spread` for page `2`, `3`,...

![Create master spread for next pages](../assets/TextboxOverflow/06-create-b-master-spread-to-next-pages.gif)

1. Right-click `A-Master`.
2. Select `Duplicate Master Spread "A-Master"`.

## Copy the text box from page `2` to `B-Master`

![Copy textbox to B-Master](../assets/TextboxOverflow/07-copy-textbox-to-b-master.gif)

1. Scroll down to page `2`.
2. Right-click the text box that the text should overflow into and choose `Copy`.
3. Double-click `B-Master`.
4. Right-click on the page and choose `Paste in Place`.

## Create a separate text box for a static heading

![Create spearate textbox for static heading](../assets/TextboxOverflow/08-create-separate-textbox-for-static-heading.gif)

1. Double-click the text box.
2. Select all text content except the heading.
3. Delete the text.
4. Adjust the text frame so it only covers the heading.

## Insert text box for dynamic content

![Create primary textbox for dynamic content](../assets/TextboxOverflow/09-make-dynamic-textbox-primary.gif)

1. Right-click on the page and choose `Paste in Place`.
2. Resize the text frame so it aligns with the heading.
3. Select all text content.
4. Delete the text.
5. Press the `Esc` key to move focus to the text frame.
6. Click the small paper icon so that a small arrow appears.

## Apply `B-Master` to page `2`

![Apply B-Master on 2 page](../assets/TextboxOverflow/10-apply-b-master-to-second-page.gif)

1. Right-click `Page 2`.
2. Select `Apply Master to Pages`.
3. Verify that `B-Master` is set next to `Apply Master:`.
4. Click `OK`.

## Move the original text box on page `2` away

![Move Page 2 non-primary textbox away](../assets/TextboxOverflow/11-move-page-2-non-primary-textbox-away.gif)

1. Double-click page `2`.
2. Click the text box.
3. Move the text box off the page.
4. Verify that the primary text frame from `B-Master` is available on the page.

## Link the text boxes together

![Link textboxes](../assets/TextboxOverflow/12-link-textboxes.gif)

1. Click the small box under the top-left corner of the text frame on page `2`.
2. Scroll up to page `1` and click the text frame you want to link it to.

## Copy the text from the moved text boxes

![Copy text into linked textbox](../assets/TextboxOverflow/13-copy-text-into-linked-textbox.gif)

1. Click inside the text box outside the page.
2. Select all the text.
3. Right-click the text and choose `Copy`.
4. Click the text frame on page `1`.
5. Right-click inside the text frame and choose `Paste`.

## Cleanup

![Cleanup delete textboxes](../assets/TextboxOverflow/14-cleanup-delete-textboxes.gif)

1. Click the text box next to page `1`.
2. Press the `Delete` key on the keyboard.
3. Do the same for the text box next to page `2`.
4. Remove the heading from the content we made static in `B-Master`.

## Verify the text overflow behavior

![Verify text overflows correctly](../assets/TextboxOverflow/15-verify-text-overflows-correctly.gif)

1. Select the text that flows onto page `2`.
2. Copy the text (right-click → `Copy` / `Ctrl + C`)
3. Paste it multiple times until a page `3` is created.
4. Verify that page `3` uses `B-Master`.
5. Undo (`Ctrl + Z`) the changes until you are back to only 2 pages.

Important: remember that you can have a maximum of 10 pages in a single spread. This is a limitation in InDesign.

[⟵](../README.md)
