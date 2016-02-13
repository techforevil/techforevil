require 'html/proofer'

task :test do
  HTML::Proofer.new('.',
                    validate_html: true,
                    ssl_verifypeer: false,
                    timeout: 30,
                    favicon: true,
                    disable_external: true
                    ).run
end

task :default => [:test]
