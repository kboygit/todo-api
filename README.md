# Restful JSON-Api

### Practicing this dependencies

    gem 'rspec-rails'
    gem 'factory_girl_rails'
    gem 'shoulda-matchers'
    gem 'database_cleaner'
    gem 'faker'

### Getting to familiarize more on rspec's expressive DSL(Domain Specific Language) TDD side of testing.

    RSpec.describe KirbyAbs, type:model do
      it { should have_many(:items).dependent(:destroy) }
      it { should validate_presence_of(:title) }
      it { should validate_presence_of(:created_by) }
    end

### Practicing more on test driven development cycle and habits.
