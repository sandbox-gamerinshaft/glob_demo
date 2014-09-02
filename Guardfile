haml_options = { format: :html5, attr_wrapper: '"', ugly: true }
guard "haml", input: "haml", output: "www", haml_options: haml_options  do
  watch %r{^haml/.+\.haml}
end
guard "sass", input: "sass", output: "www/stylesheets"
guard "coffeescript", input: "coffeescripts", output: "www/javascripts", bare: true