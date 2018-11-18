bin/rails db:migrate:reset

User.create!(name: 'admin', email: 'admin@example.com', password:'admin',password_confirmation: 'admin',admin: true)