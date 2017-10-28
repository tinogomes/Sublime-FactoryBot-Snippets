# FactoryBot Snippets for Sublime Text 2/3 (imported from old Sublime-FactoryGirl-Snippets)

## Included Snippets

### For create a new factory

* `fac` -> `factory :name, :class, :parent, :aliases do ... end`

### For factory definition

* `seq` -> `sequence(:attribute, initial value) { |n| "#{n}" }`
* `ass` -> `association :field_name, factory: :factory_name, strategy: :build/:create`
* `fbtt` -> `trait do ... end`
* `fbtr` -> `transient do ... end`
* `fbaa` -> `add_attribute(:field) { ... }`

#### ... and callbacks

* `after` -> `after(:create|:build|:stub) { |resource| ... }`
* `before` -> `before(:create) { |resource| ... }`

### Using

* `fbc` -> `create(:model, attributes)`
* `fbcl` -> `create_list(:model, 3, attributes)`
* `fbb` -> `build(:model, attributes)`
* `fbbs` -> `build_stubbed(:model, attributes)`
* `fbbl` -> `build_list(:model, 3, attributes)`
* `fbaf` -> `attributes_for(:model, attributes)`
