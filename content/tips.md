this is some markdown tips and tricks to make pages look nicer

# Callouts of text: either to say "note", "info", "tip", or "warning"
{{% notice note "Note" %}}
This is a standard "note" style.
{{% /notice %}}

The other three variants follow.

{{% notice info "Info" %}}
Here is the "info" style.
{{% /notice %}}

{{% notice tip "Tip" %}}
Here is a "tip" variant of a notice.
{{% /notice %}}

{{% notice warning "Warning" %}}
Here is the "warning" flavor of a notice.
{{% /notice %}}

Blockquotes also call out specific information
> This is a block quote
> and this continues it


# To insert an image
![Jane Doe](/images/jane-doe.png)
[give image a name](say path to image that will be in static/images folder; do not include 'static' in the path)

![Jane Doe](/images/jane-doe.png "this is a caption to the image")

![Jane Doe](/images/jane-doe.png " ") <- keep quotes empty if you do not want to caption image


# To add a table
 Name | Age
--------|------
    Bob | 27
  Alice | 23


# Text transformation
*italics*
**bold**
`code`


# Lists
1. First item
2. Second item
3. Third item

* List item
* Another item
* And another item

Nested list
* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese
