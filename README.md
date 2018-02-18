Estructura común a todos los proyectos nuevos en RUBY (tener en GitHub):
· Crear un directorio 'lib' para incluir los ficheros de código
· Crear un fichero 'ruby-version' para comentar la versión de Ruby que usamos (usar RVM)
· Crear un fichero 'Gemfile' en tu directorio
· Terminal: vim Gemfile	
· Incluir en el fichero 'Gemfile':
	source "https://rubygems.org"

	gem 'rspec', '~> 3.7'				  (copiado de "https://rubygems.org/gems/rspec")
· Terminal: gem install bundler				
			(instala la gema Bundler en mi proyecto)
· Terminal: bundler install --binstubs		
			(propios comandos de la gema los pasa a un directorio de mi proyecto)
· Se crean nuevos directorios y ficheros en el directorio del proyecto
· Terminal: bin/rspec --init
· Se crea un directorio 'spec' con un fichero '.rspec'