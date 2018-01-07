# Phoenix Dynamic Form

From http://blog.plataformatec.com.br/2016/09/dynamic-forms-with-phoenix/.
Reference so I don't keep on copying this for every new phoenix app

## Instructions
- add `import AppWeb.InputHelpers` under `view` of `lib/app_web.ex` file
- copy `input_helpers.ex` under `lib/app_web/views` folder
- rename `AppWeb`
- use inside form `<%= input f, :name %>`
