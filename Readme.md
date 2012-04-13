Create a user in rails console:

    User.create(email: "test@test.de", password: "test01", password_confirmation: "test01")

Start the server & go to localhost:3000/admin. Login with test@test.de & test01.

See 426ec4cb4c5841292739ec31cef63ca6e41ac2ea for the workaround for rolify issue 57.
