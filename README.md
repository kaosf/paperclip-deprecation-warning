# Paperclip deprecation warning sample

```bash
bundle install
rake db:migrate
rake

# DEPRECATION WARNING: String based terminators are deprecated, please use
# a lambda. (called from <class:Item> at
# /some/where/app/app/models/item.rb:2)
```

## References

* https://github.com/thoughtbot/paperclip/issues/1403
* https://github.com/thoughtbot/paperclip/pull/1404
* http://dev.mensfeld.pl/2014/05/upgrading-to-rails-4-1-from-rails-4-0-ruby-on-rails/
