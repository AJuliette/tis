## Invalid HTML will mess up your form

[Source: Stackoverflow](https://stackoverflow.com/questions/17714167/div-inside-form-rails)

I almost lost my sanity on this. 
Basically what I did was this:

```html
<div>
  <%= form_for @object, url: object_path, method: :put do |f| %>
  ...
</div>

  <%= f.fields_for(:jobs, job) do |ff| %>
  ...
<% end %>
```

And it closed my form at the `</div>`. It never happened to me before and this was a hard lesson learnt.
