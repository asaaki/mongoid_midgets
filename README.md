# MongoidMidgets

Meta gem for my microgems.

Currently:

* [mongoid_bitfield](https://github.com/asaaki/mongoid_bitfield) — helper for bitfields which are stored as a single property in mongodb
* [mongoid_touch](https://github.com/asaaki/mongoid_touch) — provides very basic touch method like known from ActiveRecord
* [mongoid_upk](https://github.com/asaaki/mongoid_upk) — change your document id generator to a more reliable one (minimizes possible id collisions)

## Usage

**The related gems are not automatically required!**

Gemfile

```ruby
gem "mongoid_midgets", :require => ["mongoid_bitfield", "mongoid_touch", "mongoid_upk"]
```

Or remove the gems you don't want to use.