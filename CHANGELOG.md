# 4.4.0

- Update rubocop to 1.27.0
- Update rubocop-ast to 1.17.0
- Update rubocop-rails to 2.14.2
- Update rubocop-rspec to 2.10.0
- Drop support for Ruby 2.6

# 4.3.0

- Update rubocop to 1.25.0
- Update rubocop-ast to 1.15.1
- Update rubocop-rails to 2.13.2
- Update rubocop-rspec to 2.7.0

# 4.2.0

- Update rubocop to 1.23.0
- Update rubocop-ast to 1.13.0
- Update rubocop-rails to 2.12.4
- Update rubocop-rspec to 2.6.0

# 4.1.0

- Update rubocop to 1.21.0
- Update rubocop-ast to 1.11.0
- Update rubocop-rails to 2.12.0
- Update rubocop-rspec to 2.4.0
- Update rubocop-rake to 0.6.0

# 4.0.0

- Update rubocop to 1.15.0
- Update rubocop-ast to 1.6.0
- Update rubocop-rails to 2.10.0
- Update rubocop-rspec to 2.3.0

# 4.0.0.pre.1

- Released as a pre-release to try surface any issues before wider rollout,
  use https://github.com/alphagov/rubocop-govuk/issues/129 to record any
  problems
- BREAKING: Upgraded from Rubocop 0.x to 1.x which introduces lots of new
  cops
- Update rubocop to 1.10.0
- Update rubocop-ast to 1.4.0
- Update rubocop-rails to 2.9.1
- Update rubocop-rspec to 2.2.0
- Make stable dependencies (>= 1.0) less strict on patch version
- Disable `SuggestExtensions` to stop Rubocop suggesting additional
  extensions at runtime
- Explicitly set target Ruby version to `>= 2.6` in gemspec
- Downgrade local Ruby version to `2.6.6` to capture lowest supported
  Ruby version
- Fix namespace change of `Capybara/FeatureMethods`
- Disable `Naming/VariableNumbers`

# 4.0.0.pre.pre.1

- Mistakenly named release, same as 4.0.0.pre.1

# 3.17.2

- Rename Blacklist to ForbiddenMethods to fix rubocop-rails warnings

# 3.17.1

- Pin rubocop-ast to 0.8.0

# 3.17.0

- Enable Rails/SaveBang
- Enable Style/DateTime
- Enforce strict Time.zone.now
- Bump rubocop to 0.87.1
- Bump rubocop-rspec to 1.42.0

# 3.16.0

- Bump and lock rubocop-rails to 2.6.0
- Bump and lock rubocop-rspec to 1.39.0

# 3.15.0

- Remove cops that are RuboCop defaults (#88)
- Disable Rails/DynamicFindBy
- Permit "and", "but" with RSpec/ContextWording

# 3.14.0

- Disable Rails/InverseOf
- Disable Rails/HasManyOrHasOneDependent
- Disable Rails/OutputSafety

# 3.13.0

- Disable Layout/FirstMethodArgumentLineBreak (#79)
- Disable Layout/MultilineMethodArgumentLineBreaks (#80)

# 3.12.0

- Disable Rails/HasAndBelongsToMany (#77)

# 3.11.0

- Add optional config for RSpec Cops (#75)
- Enable Style/Next (#74)
- Partially enable Rails/SkipsModelValidations (#74)
- Partially enable Rails/Output (#74)
- Enable Rails/HasAndBelongsToMany (#74)
- Enable Bundler/DuplicatedGem (#74)

# 3.10.0

* Enable Style/NegatedIf (#71)
* Enable Style/GlobalVars (#71)
* Enable Style/RaiseArgs (#71)
* Enable Style/MethodDefParentheses (#71)
* Enable Style/NumericLiterals (#71)
* Enable Layout/MultilineArrayLineBreaks (#63)
* Enable Layout/MultilineHashKeyLineBreaks (#63)
* Enable Layout/MultilineMethodArgumentLineBreaks (#63)
* Enable Layout/FirstMethodArgumentLineBreak (#63)
* Fix bug with Style/FormatString (#70)

# 3.9.0

* Enable Style/Alias (#60)
* Enable Style/AsciiComments (#60)
* Enable Style/BlockDelimiters (#60)
* Enable Style/CaseEquality (#60)
* Enable Style/PreferredHashMethods (#60)
* Enable Style/DoubleNegation (#60)
* Enable Style/FormatString (#60)
* Enable Style/Encoding (#64)
* Enable Style/IfWithSemicolon (#64)
* Enable Style/Lambda (#64)
* Enable Style/LambdaCall (#64)
* Enable Style/ModuleFunction (#64)
* Enable Style/NilComparison (#64)
* Enable Style/SignalException (#64)
* Enable Style/SingleLineMethods (#64)
* Enable Style/CommandLiteral (#64)
* Disable Metrics/BlockLength (#65, #68)

# 3.8.0

* Enable check for flip-flops (#55)
* Enable Layout/FirstArrayElementIndentation (#56)
* Enable Layout/FirstHashElementIndentation (#56)
* Enable Naming/AsciiIdentifiers (#58)
* Enable Naming/FileName (#58)
* Enable Rails/ActionFilter (#59)
* Enable Rails/ScopeArgs (#59)

# 3.7.0

* Turn a load of Cops back on (#52)

# 3.6.0

* Remove config that matches RuboCop defaults (#47)
* Reorganise all the Cops (#44)

# 3.5.0

* Disable pending cops by default (#37)

# 3.4.0

* Add rubocop-rake cops (#32)
* Revert #27 (hash transform cops) (#31)

# 3.3.2

* Exclude /tmp directory (#29)

# 3.3.1

* Exclude two unsafe style cops (#27)

# 3.3.0

* Exclude Rails migrations from linting checks (#25)

# 3.2.0

* Configure new cops about hash styles (#24)
* Exclude `tmp` directory from linting checks (#22)

# 3.1.0

* Fix deprecation warning for AllCops/Excludes => AllCops/Exclude (#17)
* Exclude `config.ru` from linter checks (#18)

# 3.0.0

* Update Rubocop to 0.80.1
  * This deletes the Style/BracesAroundHashParameters cop for future
    Ruby 3 compatibility.
* Exclude `bin` directory and `db/schema.rb` from linter checks (#14)

# 2.0.0

* Use specific version for RuboCop
* Update RuboCop to 0.77

# 1.0.0

* Allow importing of Ruby and Rails rules seperately

# 0.2.0

* Disable the Style/FormatStringToken cop

# 0.1.0

* Initial release with previous work from `govuk-lint`
