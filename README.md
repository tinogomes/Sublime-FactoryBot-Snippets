# FactoryBot Snippets for Sublime Text 2/3 (imported from old Sublime-FactoryGirl-Snippets)

## Included Snippets

`fac` -> `factory :name, :class, :parent, :aliases do ... end`

`seq` -> `sequence(:attribute, initial value) { |n| "#{n}" }`

`fbaf` -> `attributes_for(:model, attributes)`

`fbc` -> `create(:model, attributes)`

`fbcl` -> `create_list(:model, 3, attributes)`

`fbb` -> `build(:model, attributes)`

`fbbs` -> `build_stubbed(:model, attributes)`

`fbbl` -> `build_list(:model, 3, attributes)`

`after` -> `after(:create|:build|:stub) { |resource| ... }`

`before` -> `before(:create) { |resource| ... }`
