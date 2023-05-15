---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

# How Spriggan uses private DataLayer tables to authenticate and verify published content

Chia's DataLayer is an amazing tool capable of creating public and auditable decentralized databases like the Climate Action Data Trust. But it can also be used on a much smaller scale to authenticate and verify user data in a decentralized way.

If you are unfamiliar with what I am building, Spriggan is a platform for truly decentralized publishing of PC games, decentralized apps, and eventually other forms of media.

Using our open source tools, creators can create and manage their own private DataLayer data store of products, which can be shared with trusted marketplaces which provide a storefront and discoverability for their products. This private data includes torrent files and passwords to decrypt their content, which stay private between the creator, trusted marketplaces, and customers who have purchased the content.

Unless the owner of a DataLayer data store publishes a mirror, the data is not public. Only the hash of the data is put on the blockchain. It is however, publicly verifiable using that hash. Marketplaces and end users can always check the hash to be sure that the product they downloaded is exactly what the author published.

Using this system, simplifies publishing greatly because marketplaces do not have to care where their data came from, only that it is legitimate. User authentication is not necessary. When a marketplace receives an update for a product, or a request to list a new product, they only need to check that the hash of the data matches the hash on the blockchain to know that the update is legitimate.

For more information, or to get involved in the future of open source publishing, check out our github, or come say hi on our Discord.

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
