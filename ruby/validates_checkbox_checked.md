## Validates checkbox checked

Source: [Guides Ruby on Rails](https://guides.rubyonrails.org/active_record_validations.html#acceptance)

I looked up how to validate that a checkbox was checked and there's one validation already here for you:

```ruby
validates :give_my_soul_to_you, acceptance: true
```
