### bundler
--- 
https://bundler.io/

https://github.com/bundler/bundler


```sh
bundle install
bundle update
bundle exec 
bundle config

```

```rb
Bundler.with_clearn_env do
  `brew install wget`
end

Bundler.with_clean_env do
  Dir.chdir "/other/bundler/project" do
    `bundle exec ./script`
  end
end

Bundler.clean_system('brew install wget')
Bundler.clean_exec('brew install wget')
```

```

```


