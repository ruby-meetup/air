source 'https://rubygems.org'

ruby '2.6.3'

gem 'rails', '~> 6.0.0'                    # Rails framework
gem 'pg', '>= 0.18', '< 2.0'               # Database for Active Record
gem 'puma', '~> 3.11'                      # Fast and concurrent web server
gem 'bootsnap', '>= 1.4.2', require: false # Speed up Rails boot time
gem 'turbolinks', '~> 5'                   # Faster web application navigation
gem 'rest-client', '~> 2.1'                # Basic HTTP Client
gem 'bh', '~> 1.2'                         # Bootstrap helpers
gem 'turbolinks_render'
gem 'pusher', '~> 1.3'                     # Websocket publisher

group :production do
  gem 'sidekiq', '~> 5.0'                  # Background processor
end

group :development, :test do
  gem 'spring'                             # Speed up local development
  gem 'spring-watcher-listen', '~> 2.0.0'  # Speed up local development
  gem 'listen', '>= 3.0.5', '< 3.2'        # Speed up local development
end

group :test do
  gem 'rspec-rails', '>= 3.7', '< 4.0'     # Testing framework
end
