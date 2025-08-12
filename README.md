# README

If Turbo doesn't work! \
Aka data: { turbo_confirm: "Are you sure?" } doesn't work \
Add this to the body in application.html.erb
```erb
<body>
  ...
  <%= javascript_include_tag "turbo", type: "module" %>
</body>
```