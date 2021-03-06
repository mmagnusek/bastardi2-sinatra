namespace :db do
  task :load_config do
    require 'active_record'
    ActiveRecord::Base.establish_connection(
      :adapter => 'sqlite3',
      :database =>  'production.db'
    )
    class Projection < ActiveRecord::Base
      scope :current, lambda { { :conditions => ['date == ?', Date.today] } }
    end
  end
  
  desc "Migrate the database"
  task(:migrate => :load_config ) do
    # ActiveRecord::Base.logger = Logger.new(STDOUT)
    ActiveRecord::Migration.verbose = true
    ActiveRecord::Migrator.migrate("db/migrate")
  end
  
  task(:seed => :load_config) do
    Projection.create :date => '2011-10-28', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-10-28', :location => 'Slaný'
    Projection.create :date => '2011-10-28', :location => 'Nové Město n. Metují'
    Projection.create :date => '2011-10-28', :location => 'Modřanský bio.'
    Projection.create :date => '2011-10-28', :location => 'Karviná'
    Projection.create :date => '2011-10-28', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-10-28', :location => 'Chomutov'
    Projection.create :date => '2011-10-28', :location => 'Třinec'
    Projection.create :date => '2011-10-28', :location => 'Hodonín'
    Projection.create :date => '2011-10-28', :location => 'Žďár n.Sáz.'
    Projection.create :date => '2011-10-28', :location => 'N.Bor'
    Projection.create :date => '2011-10-28', :location => 'GAC Zlín'
    Projection.create :date => '2011-10-28', :location => 'Třebíč'
    Projection.create :date => '2011-10-28', :location => 'Teplice'
    Projection.create :date => '2011-10-28', :location => 'Tanvald'
    Projection.create :date => '2011-10-28', :location => 'Varnsdorf'
    Projection.create :date => '2011-10-28', :location => 'Velešín'
    Projection.create :date => '2011-10-28', :location => 'Písek'
    Projection.create :date => '2011-10-28', :location => 'J.Hradec'
    Projection.create :date => '2011-10-28', :location => 'Přerov'
    Projection.create :date => '2011-10-28', :location => 'Kolín'
    Projection.create :date => '2011-10-28', :location => 'Klatovy'
    Projection.create :date => '2011-10-28', :location => 'K.Hora'
    Projection.create :date => '2011-10-28', :location => 'Mar.Lázně'
    Projection.create :date => '2011-10-28', :location => 'Čes.Lípa'
    Projection.create :date => '2011-10-28', :location => 'Chodov'
    Projection.create :date => '2011-10-28', :location => 'Rakovník'
    Projection.create :date => '2011-10-28', :location => 'Vsetín'
    Projection.create :date => '2011-10-28', :location => 'Strakonice'
    Projection.create :date => '2011-10-28', :location => 'Svitavy'
    Projection.create :date => '2011-10-28', :location => 'Litoměřice'
    Projection.create :date => '2011-10-28', :location => 'Cheb'
    Projection.create :date => '2011-10-28', :location => 'Jirkov'
    Projection.create :date => '2011-10-28', :location => 'Čáslav'
    Projection.create :date => '2011-10-28', :location => 'Kopřivnice'
    Projection.create :date => '2011-10-28', :location => 'Louny'
    Projection.create :date => '2011-10-28', :location => 'Náchod'
    Projection.create :date => '2011-10-28', :location => 'Kadaň'
    Projection.create :date => '2011-10-28', :location => 'Turnov'
    Projection.create :date => '2011-10-28', :location => 'Kladno'
    Projection.create :date => '2011-10-28', :location => 'Jablonec n.Ni-Radnice'
    Projection.create :date => '2011-10-28', :location => 'Praha – Atlas'
    Projection.create :date => '2011-10-28', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-10-28', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-10-28', :location => 'Cinema City – Plzeň Plaza'
    Projection.create :date => '2011-10-28', :location => 'Cinema City – Brno Olympia'
    Projection.create :date => '2011-10-28', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-10-28', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-10-28', :location => 'CineStar - Černý M.'
    Projection.create :date => '2011-10-28', :location => 'CineStar - Anděl'
    Projection.create :date => '2011-10-28', :location => 'CineStar - Liberec'
    Projection.create :date => '2011-10-28', :location => 'CineStar - Plzeň'
    Projection.create :date => '2011-10-28', :location => 'CineStar - Hradec Kr.'
    Projection.create :date => '2011-10-28', :location => 'CineStar - ČB'
    Projection.create :date => '2011-10-28', :location => 'CineStar - Pardubice'
    Projection.create :date => '2011-10-28', :location => 'CineStar - Olomouc'
    Projection.create :date => '2011-10-28', :location => 'CineStar - Ostrava'
    Projection.create :date => '2011-10-28', :location => 'GAC Zlín'
    Projection.create :date => '2011-10-29', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-10-29', :location => 'Slaný'
    Projection.create :date => '2011-10-29', :location => 'Nové Město n. Metují'
    Projection.create :date => '2011-10-29', :location => 'Modřanský bio.'
    Projection.create :date => '2011-10-29', :location => 'Karviná'
    Projection.create :date => '2011-10-29', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-10-29', :location => 'Chomutov'
    Projection.create :date => '2011-10-29', :location => 'Třinec'
    Projection.create :date => '2011-10-29', :location => 'Hodonín'
    Projection.create :date => '2011-10-29', :location => 'N.Bor'
    Projection.create :date => '2011-10-29', :location => 'GAC Zlín'
    Projection.create :date => '2011-10-29', :location => 'Třebíč'
    Projection.create :date => '2011-10-29', :location => 'Teplice'
    Projection.create :date => '2011-10-29', :location => 'Tanvald'
    Projection.create :date => '2011-10-29', :location => 'Varnsdorf'
    Projection.create :date => '2011-10-29', :location => 'Písek'
    Projection.create :date => '2011-10-29', :location => 'Hrádek n.N.'
    Projection.create :date => '2011-10-29', :location => 'Přerov'
    Projection.create :date => '2011-10-29', :location => 'Kolín'
    Projection.create :date => '2011-10-29', :location => 'Klatovy'
    Projection.create :date => '2011-10-29', :location => 'Mar.Lázně'
    Projection.create :date => '2011-10-29', :location => 'Čes.Lípa'
    Projection.create :date => '2011-10-29', :location => 'Bohumín'
    Projection.create :date => '2011-10-29', :location => 'Chodov'
    Projection.create :date => '2011-10-29', :location => 'Rakovník'
    Projection.create :date => '2011-10-29', :location => 'Vsetín'
    Projection.create :date => '2011-10-29', :location => 'Strakonice'
    Projection.create :date => '2011-10-29', :location => 'Svitavy'
    Projection.create :date => '2011-10-29', :location => 'Počátky'
    Projection.create :date => '2011-10-29', :location => 'Třeboň'
    Projection.create :date => '2011-10-29', :location => 'Litoměřice'
    Projection.create :date => '2011-10-29', :location => 'Cheb'
    Projection.create :date => '2011-10-29', :location => 'Jirkov'
    Projection.create :date => '2011-10-29', :location => 'Čáslav'
    Projection.create :date => '2011-10-29', :location => 'Louny'
    Projection.create :date => '2011-10-29', :location => 'Dobřany'
    Projection.create :date => '2011-10-29', :location => 'Náchod'
    Projection.create :date => '2011-10-29', :location => 'Kralupy n.Vltavou'
    Projection.create :date => '2011-10-29', :location => 'Turnov'
    Projection.create :date => '2011-10-29', :location => 'Kladno'
    Projection.create :date => '2011-10-29', :location => 'Praha – Atlas'
    Projection.create :date => '2011-10-29', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-10-29', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-10-29', :location => 'Cinema City – Plzeň Plaza'
    Projection.create :date => '2011-10-29', :location => 'Cinema City – Brno Olympia'
    Projection.create :date => '2011-10-29', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-10-29', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-10-29', :location => 'CineStar - Černý M.'
    Projection.create :date => '2011-10-29', :location => 'CineStar - Anděl'
    Projection.create :date => '2011-10-29', :location => 'CineStar - Liberec'
    Projection.create :date => '2011-10-29', :location => 'CineStar - Plzeň'
    Projection.create :date => '2011-10-29', :location => 'CineStar - Hradec Kr.'
    Projection.create :date => '2011-10-29', :location => 'CineStar - ČB'
    Projection.create :date => '2011-10-29', :location => 'CineStar - Pardubice'
    Projection.create :date => '2011-10-29', :location => 'CineStar - Olomouc'
    Projection.create :date => '2011-10-29', :location => 'CineStar - Ostrava'
    Projection.create :date => '2011-10-29', :location => 'Uničov'
    Projection.create :date => '2011-10-29', :location => 'GAC Zlín'
    Projection.create :date => '2011-10-30', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-10-30', :location => 'Slaný'
    Projection.create :date => '2011-10-30', :location => 'Modřanský bio.'
    Projection.create :date => '2011-10-30', :location => 'Karviná'
    Projection.create :date => '2011-10-30', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-10-30', :location => 'Chomutov'
    Projection.create :date => '2011-10-30', :location => 'Třinec'
    Projection.create :date => '2011-10-30', :location => 'Hodonín'
    Projection.create :date => '2011-10-30', :location => 'N.Bor'
    Projection.create :date => '2011-10-30', :location => 'GAC Zlín'
    Projection.create :date => '2011-10-30', :location => 'Třebíč'
    Projection.create :date => '2011-10-30', :location => 'Teplice'
    Projection.create :date => '2011-10-30', :location => 'Varnsdorf'
    Projection.create :date => '2011-10-30', :location => 'Hrádek n.N.'
    Projection.create :date => '2011-10-30', :location => 'Přerov'
    Projection.create :date => '2011-10-30', :location => 'Kolín'
    Projection.create :date => '2011-10-30', :location => 'Klatovy'
    Projection.create :date => '2011-10-30', :location => 'K.Hora'
    Projection.create :date => '2011-10-30', :location => 'Mar.Lázně'
    Projection.create :date => '2011-10-30', :location => 'Čes.Lípa'
    Projection.create :date => '2011-10-30', :location => 'Bohumín'
    Projection.create :date => '2011-10-30', :location => 'Chodov'
    Projection.create :date => '2011-10-30', :location => 'Vsetín'
    Projection.create :date => '2011-10-30', :location => 'Strakonice'
    Projection.create :date => '2011-10-30', :location => 'Svitavy'
    Projection.create :date => '2011-10-30', :location => 'Litoměřice'
    Projection.create :date => '2011-10-30', :location => 'Cheb'
    Projection.create :date => '2011-10-30', :location => 'Kopřivnice'
    Projection.create :date => '2011-10-30', :location => 'Louny'
    Projection.create :date => '2011-10-30', :location => 'Náchod'
    Projection.create :date => '2011-10-30', :location => 'Kadaň'
    Projection.create :date => '2011-10-30', :location => 'Turnov'
    Projection.create :date => '2011-10-30', :location => 'Kladno'
    Projection.create :date => '2011-10-30', :location => 'Praha – Atlas'
    Projection.create :date => '2011-10-30', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-10-30', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-10-30', :location => 'Cinema City – Plzeň Plaza'
    Projection.create :date => '2011-10-30', :location => 'Cinema City – Brno Olympia'
    Projection.create :date => '2011-10-30', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-10-30', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-10-30', :location => 'CineStar - Černý M.'
    Projection.create :date => '2011-10-30', :location => 'CineStar - Anděl'
    Projection.create :date => '2011-10-30', :location => 'CineStar - Liberec'
    Projection.create :date => '2011-10-30', :location => 'CineStar - Plzeň'
    Projection.create :date => '2011-10-30', :location => 'CineStar - Hradec Kr.'
    Projection.create :date => '2011-10-30', :location => 'CineStar - ČB'
    Projection.create :date => '2011-10-30', :location => 'CineStar - Pardubice'
    Projection.create :date => '2011-10-30', :location => 'CineStar - Olomouc'
    Projection.create :date => '2011-10-30', :location => 'CineStar - Ostrava'
    Projection.create :date => '2011-10-30', :location => 'Hradec Králové-Central'
    Projection.create :date => '2011-10-30', :location => 'Uničov'
    Projection.create :date => '2011-10-30', :location => 'GAC Zlín'
    Projection.create :date => '2011-10-31', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-10-31', :location => 'Slaný'
    Projection.create :date => '2011-10-31', :location => 'Jihlava-Dukla'
    Projection.create :date => '2011-10-31', :location => 'Modřanský bio.'
    Projection.create :date => '2011-10-31', :location => 'Karviná'
    Projection.create :date => '2011-10-31', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-10-31', :location => 'Chomutov'
    Projection.create :date => '2011-10-31', :location => 'GAC Zlín'
    Projection.create :date => '2011-10-31', :location => 'Varnsdorf'
    Projection.create :date => '2011-10-31', :location => 'K.Hora'
    Projection.create :date => '2011-10-31', :location => 'Vsetín'
    Projection.create :date => '2011-10-31', :location => 'Ostrava-Minikino'
    Projection.create :date => '2011-10-31', :location => 'Strakonice'
    Projection.create :date => '2011-10-31', :location => 'Litoměřice'
    Projection.create :date => '2011-10-31', :location => 'Beroun'
    Projection.create :date => '2011-10-31', :location => 'Kopřivnice'
    Projection.create :date => '2011-10-31', :location => 'K.Vary'
    Projection.create :date => '2011-10-31', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-10-31', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-10-31', :location => 'Cinema City – Plzeň Plaza'
    Projection.create :date => '2011-10-31', :location => 'Cinema City – Brno Olympia'
    Projection.create :date => '2011-10-31', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-10-31', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-10-31', :location => 'CineStar - Černý M.'
    Projection.create :date => '2011-10-31', :location => 'CineStar - Anděl'
    Projection.create :date => '2011-10-31', :location => 'CineStar - Liberec'
    Projection.create :date => '2011-10-31', :location => 'CineStar - Plzeň'
    Projection.create :date => '2011-10-31', :location => 'CineStar - Hradec Kr.'
    Projection.create :date => '2011-10-31', :location => 'CineStar - ČB'
    Projection.create :date => '2011-10-31', :location => 'CineStar - Pardubice'
    Projection.create :date => '2011-10-31', :location => 'CineStar - Olomouc'
    Projection.create :date => '2011-10-31', :location => 'CineStar - Ostrava'
    Projection.create :date => '2011-10-31', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-1', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-11-1', :location => 'Kroměříž'
    Projection.create :date => '2011-11-1', :location => 'Jihlava-Dukla'
    Projection.create :date => '2011-11-1', :location => 'Modřanský bio.'
    Projection.create :date => '2011-11-1', :location => 'Karviná'
    Projection.create :date => '2011-11-1', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-11-1', :location => 'Chomutov'
    Projection.create :date => '2011-11-1', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-1', :location => 'Varnsdorf'
    Projection.create :date => '2011-11-1', :location => 'Vsetín'
    Projection.create :date => '2011-11-1', :location => 'Ostrava-Minikino'
    Projection.create :date => '2011-11-1', :location => 'Beroun'
    Projection.create :date => '2011-11-1', :location => 'Louny'
    Projection.create :date => '2011-11-1', :location => 'K.Vary'
    Projection.create :date => '2011-11-1', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-11-1', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-11-1', :location => 'Cinema City – Plzeň Plaza'
    Projection.create :date => '2011-11-1', :location => 'Cinema City – Brno Olympia'
    Projection.create :date => '2011-11-1', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-11-1', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-11-1', :location => 'CineStar - Černý M.'
    Projection.create :date => '2011-11-1', :location => 'CineStar - Anděl'
    Projection.create :date => '2011-11-1', :location => 'CineStar - Liberec'
    Projection.create :date => '2011-11-1', :location => 'CineStar - Plzeň'
    Projection.create :date => '2011-11-1', :location => 'CineStar - Hradec Kr.'
    Projection.create :date => '2011-11-1', :location => 'CineStar - ČB'
    Projection.create :date => '2011-11-1', :location => 'CineStar - Pardubice'
    Projection.create :date => '2011-11-1', :location => 'CineStar - Olomouc'
    Projection.create :date => '2011-11-1', :location => 'CineStar - Ostrava'
    Projection.create :date => '2011-11-1', :location => 'Boskovice'
    Projection.create :date => '2011-11-1', :location => 'Hradec Králové-Central'
    Projection.create :date => '2011-11-1', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-2', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-11-2', :location => 'Heřmanův městec'
    Projection.create :date => '2011-11-2', :location => 'Kroměříž'
    Projection.create :date => '2011-11-2', :location => 'Jihlava-Dukla'
    Projection.create :date => '2011-11-2', :location => 'Modřanský bio.'
    Projection.create :date => '2011-11-2', :location => 'Karviná'
    Projection.create :date => '2011-11-2', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-11-2', :location => 'Chomutov'
    Projection.create :date => '2011-11-2', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-2', :location => 'Varnsdorf'
    Projection.create :date => '2011-11-2', :location => 'Semily'
    Projection.create :date => '2011-11-2', :location => 'Beroun'
    Projection.create :date => '2011-11-2', :location => 'Louny'
    Projection.create :date => '2011-11-2', :location => 'Kralupy n.Vltavou'
    Projection.create :date => '2011-11-2', :location => 'K.Vary'
    Projection.create :date => '2011-11-2', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-11-2', :location => 'Cinema City – Zličín'
    Projection.create :date => '2011-11-2', :location => 'Cinema City – Plzeň Plaza'
    Projection.create :date => '2011-11-2', :location => 'Cinema City – Brno Olympia'
    Projection.create :date => '2011-11-2', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-11-2', :location => 'Cinema City – Pardubice'
    Projection.create :date => '2011-11-2', :location => 'CineStar - Černý M.'
    Projection.create :date => '2011-11-2', :location => 'CineStar - Anděl'
    Projection.create :date => '2011-11-2', :location => 'CineStar - Liberec'
    Projection.create :date => '2011-11-2', :location => 'CineStar - Plzeň'
    Projection.create :date => '2011-11-2', :location => 'CineStar - Hradec Kr.'
    Projection.create :date => '2011-11-2', :location => 'CineStar - ČB'
    Projection.create :date => '2011-11-2', :location => 'CineStar - Pardubice'
    Projection.create :date => '2011-11-2', :location => 'CineStar - Olomouc'
    Projection.create :date => '2011-11-2', :location => 'CineStar - Ostrava'
    Projection.create :date => '2011-11-2', :location => 'Frýdek Místek'
    Projection.create :date => '2011-11-2', :location => 'Boskovice'
    Projection.create :date => '2011-11-3', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-11-3', :location => 'Kroměříž'
    Projection.create :date => '2011-11-3', :location => 'Jihlava-Dukla'
    Projection.create :date => '2011-11-3', :location => 'Most'
    Projection.create :date => '2011-11-3', :location => 'Bruntál'
    Projection.create :date => '2011-11-3', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-11-3', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-3', :location => 'Semily'
    Projection.create :date => '2011-11-3', :location => 'Pelhřimov'
    Projection.create :date => '2011-11-3', :location => 'Trhové Sviny'
    Projection.create :date => '2011-11-3', :location => 'Beroun'
    Projection.create :date => '2011-11-3', :location => 'Kadaň'
    Projection.create :date => '2011-11-3', :location => 'Jablonec n.Ni-Radnice'
    Projection.create :date => '2011-11-3', :location => 'Příbram'
    Projection.create :date => '2011-11-3', :location => 'Uherský Brod'
    Projection.create :date => '2011-11-3', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-4', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-11-4', :location => 'Č.Těšín'
    Projection.create :date => '2011-11-4', :location => 'Kroměříž'
    Projection.create :date => '2011-11-4', :location => 'Jihlava-Dukla'
    Projection.create :date => '2011-11-4', :location => 'Most'
    Projection.create :date => '2011-11-4', :location => 'Bruntál'
    Projection.create :date => '2011-11-4', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-11-4', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-4', :location => 'Semily'
    Projection.create :date => '2011-11-4', :location => 'Suchdol'
    Projection.create :date => '2011-11-4', :location => 'Pelhřimov'
    Projection.create :date => '2011-11-4', :location => 'Trhové Sviny'
    Projection.create :date => '2011-11-4', :location => 'Kadaň'
    Projection.create :date => '2011-11-4', :location => 'Uherský Brod'
    Projection.create :date => '2011-11-4', :location => 'Hradec Králové-Central'
    Projection.create :date => '2011-11-4', :location => 'Poděbrady'
    Projection.create :date => '2011-11-4', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-5', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-11-5', :location => 'Č.Těšín'
    Projection.create :date => '2011-11-5', :location => 'Jihlava-Dukla'
    Projection.create :date => '2011-11-5', :location => 'Most'
    Projection.create :date => '2011-11-5', :location => 'Bruntál'
    Projection.create :date => '2011-11-5', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-11-5', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-5', :location => 'Kyjov'
    Projection.create :date => '2011-11-5', :location => 'Kadaň'
    Projection.create :date => '2011-11-5', :location => 'Poděbrady'
    Projection.create :date => '2011-11-5', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-6', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-11-6', :location => 'Č.Těšín'
    Projection.create :date => '2011-11-6', :location => 'Holešov'
    Projection.create :date => '2011-11-6', :location => 'Jihlava-Dukla'
    Projection.create :date => '2011-11-6', :location => 'Most'
    Projection.create :date => '2011-11-6', :location => 'Bruntál'
    Projection.create :date => '2011-11-6', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-11-6', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-6', :location => 'Veselí n. Moravou'
    Projection.create :date => '2011-11-6', :location => 'Kyjov'
    Projection.create :date => '2011-11-6', :location => 'Kadaň'
    Projection.create :date => '2011-11-6', :location => 'Poděbrady'
    Projection.create :date => '2011-11-6', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-7', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-11-7', :location => 'Orlová-Vesmír'
    Projection.create :date => '2011-11-7', :location => 'Most'
    Projection.create :date => '2011-11-7', :location => 'Bruntál'
    Projection.create :date => '2011-11-7', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-11-7', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-7', :location => 'Třeboň'
    Projection.create :date => '2011-11-7', :location => 'Cheb'
    Projection.create :date => '2011-11-7', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-8', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-11-8', :location => 'Orlová-Vesmír'
    Projection.create :date => '2011-11-8', :location => 'Chrudim'
    Projection.create :date => '2011-11-8', :location => 'Doksy'
    Projection.create :date => '2011-11-8', :location => 'Most'
    Projection.create :date => '2011-11-8', :location => 'Bruntál'
    Projection.create :date => '2011-11-8', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-11-8', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-8', :location => 'Cheb'
    Projection.create :date => '2011-11-8', :location => 'Kadaň'
    Projection.create :date => '2011-11-8', :location => 'Sokolov'
    Projection.create :date => '2011-11-8', :location => 'Hranice'
    Projection.create :date => '2011-11-8', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-9', :location => 'CineStar – Jihlava'
    Projection.create :date => '2011-11-9', :location => 'Orlová-Vesmír'
    Projection.create :date => '2011-11-9', :location => 'Most'
    Projection.create :date => '2011-11-9', :location => 'Bruntál'
    Projection.create :date => '2011-11-9', :location => 'CineStar – Ml. Boleslav'
    Projection.create :date => '2011-11-9', :location => 'GAC Zlín'
    Projection.create :date => '2011-11-9', :location => 'Cheb'
    Projection.create :date => '2011-11-9', :location => 'Sokolov'
    Projection.create :date => '2011-11-9', :location => 'Kladno'
    Projection.create :date => '2011-11-9', :location => 'Blansko'
    Projection.create :date => '2011-11-9', :location => 'GAC Zlín'
  end
  
  task(:seed2 => :load_config) do
    create_projection('11/15/2011',"Havířov;Liberec Lípa;K.Vary Drahomíra;Brno Lucerna;Golden Apple Cinema Zlín;Šumperk;Náchod;Prostějov;Val.Meziříčí;Cinema City Zličín;Cinema City Plzeň Plaza;Cinema City Modřice Olympia;Cinema City Pardubice;CineStar Černý Most;CineStar Anděl;CineStar Liberec;CineStar Plzeň;CineStar Hradec Králové;CineStar České Budějovice;CineStar Pardubice;CineStar Olomouc;CineStar Ostrava;CineStar Mladá Boleslav;CineStar Jihlava")
    create_projection('11/16/2011',"Havířov;Hradec n. Moravicí;K.Vary Drahomíra;Brno Lucerna;Neratov.;Golden Apple Cinema Zlín;Prostějov;Val.Meziříčí;Cinema City Zličín;Cinema City Plzeň Plaza;Cinema City Modřice Olympia;Cinema City Pardubice;CineStar Černý Most;CineStar Anděl;CineStar Liberec;CineStar Plzeň;CineStar Hradec Králové;CineStar České Budějovice;CineStar Pardubice;CineStar Olomouc;CineStar Ostrava;CineStar Mladá Boleslav;CineStar Jihlava;Soběslav")
    create_projection('11/17/2011',"Ostrava-ART FK;Benešov;Choceň;Ostrov;Nové M.na Moravě")
    create_projection('11/18/2011',"Kostelec n.Orlicí;Vlašim;Trutnov;Nové M.na Moravě;Neratov.")
    create_projection('11/19/2011',"Chrudim;Červený Kostelec;Benešov;Trutnov;Ostrov;Nové M.n.Metují;Třeboň")
    create_projection('11/20/2011',"Chrudim;Benešov;Trutnov;Ostrov;Nové M.n.Metují")
    create_projection('11/21/2011',"Mělník;Zábřeh;Třinec")
    create_projection('11/22/2011',"Mělník;Lysá n.L.;Kralovice;Vysoké mýto;Třinec")
    create_projection('11/23/2011',"Chrudim;Mělník;Brandýs;Kaznějov;Letohrad;Třinec;Vyškov")
    create_projection('11/24/2011',"Klášterec n.O.;Havl.Brod;Tachov;Tábor;Děčín")
    create_projection('11/25/2011',"Klášterec n.O.;Havl.Brod;Tábor;Horažďovice;Děčín;Teplice;Praha-Bio Oko")
    create_projection('11/26/2011',"Havl.Brod;Choceň;Tábor;Horažďovice;Děčín;Teplice;Litoměřice")
    create_projection('11/27/2011',"Krupka;Choceň;Tábor;Děčín;Litoměřice")
    create_projection('11/28/2011',"Litvínov;Krupka;Vodňany;Čáslav")
    create_projection('11/29/2011',"Litvínov;Štětí;Uničov;Kynšperk;Litomyšl;Fulnek;Čes.Lípa")
    create_projection('11/30/2011',"Litvínov;Štětí;Uničov;Šluknov;Litomyšl;Šternberk;Čes.Lípa;Beroun;Břeclav")
    create_projection('12/1/2011',"Domažlice;Příbram")
    create_projection('12/2/2011',"Nové M.n.Metují;Krásná Lípa;Domažlice;Frenštát p. R.;Chrudim;Nová Paka")
    create_projection('12/3/2011',"Nové M.n.Metují;Lomnice n.Popelkou;Nové Hrady;Frenštát p. R.;Tanvald")
    create_projection('12/4/2011',"Bečov;Lomnice n.Popelkou;Frenštát p. R.")
    create_projection('12/5/2011',"Č.Krumlov")
    create_projection('12/6/2011',"Kdyně;Police n.Metují;Č.Krumlov;Tišnov")
    create_projection('12/7/2011',"Kdyně;Mohelnice;Č.Krumlov;Ivančice;Městec Králové;Ivanovice")
    create_projection('12/8/2011',"Chlumec n. Cidlinou;Nymburk")
    create_projection('12/9/2011',"Rožnov p. Radh.;Přelouč;Mimoň;Sedlčany;Hluboká n.Vltavou;Nymburk;Pacov")
    create_projection('12/10/2011',"Rožnov p. Radh.;Dolní Podluží;Kosova Hora")
    create_projection('12/11/2011',"Rožnov p. Radh.;Kelč")
    create_projection('12/12/2011',"Bohumín K3;Třeboň")
    create_projection('12/13/2011',"Nový Bydžov;Rožmitál p.Tř.;Planá;Horní Slavkov")
    create_projection('12/14/2011',"Protivín;Český Brod;Dvůr Králové;Hostinné")
    create_projection('12/15/2011',"Dvůr Králové")
    create_projection('12/16/2011',"Mikulov;Ždírec n.Doub.;Třeboň")
    create_projection('12/17/2011',"Slavkov u Brna;Vratimov")
    create_projection('12/18/2011',"Klimkovice;Slavkov u Brna;Č.Meziříčí")
    create_projection('12/19/2011',"Třešť;Lanškroun")
    create_projection('12/20/2011',"Lanškroun")
    create_projection('12/21/2011',"Rumburk")
    create_projection('12/28/2011',"Stříbro")
    create_projection('1/3/2012',"Kaplice")
    create_projection('1/6/2012',"Senice na Hané;Bohušovice")
    create_projection('1/7/2012',"Jablonec n. Jizerou;Dolní Cerekev;Čerčany;Bohuňovice")
    create_projection('1/10/2012',"Podbořany;Bechyně")
    create_projection('1/11/2012',"Kunovice;KC Spořilov;Bechyně")
    create_projection('1/12/2012',"Lomnice nad Popelkou")
    create_projection('1/13/2012',"Brodek u Přerova;Janské Lázně")
    create_projection('1/14/2012',"Kyselka;Krucemburk;Ml. Vožice")
    create_projection('1/15/2012',"Rosice;Lázně Bělohrad")
    create_projection('1/18/2012',"Sezimovo Ústí;Bor u Tachova;Habartov")
    create_projection('1/19/2012',"Jablonné n.Orlicí")
    create_projection('1/20/2012',"Luka nad Jihlavou;Kdyně;Velké Němčice;Mnichovo Hradiště")
    create_projection('1/21/2012',"Kdyně;Hluk")
    create_projection('1/22/2012',"Dlouhá Loučka;Hluk")
    create_projection('1/24/2012',"Holice")
    create_projection('1/27/2012',"Velké Opatovice")
    create_projection('1/28/2012',"Vejprty")
    create_projection('1/29/2012',"Vejprty")
  end
  
  task(:seed3 => :load_config) do
    create_projection('11/30/2011',"Cinema City Zličín;Cinema City Plzeň Plaza;CineStar Plzeň;CineStar České Budějovice;CineStar Ostrava;CineStar Mladá Boleslav")
    create_projection('12/3/2011',"Jablonec")
    create_projection('12/4/2011',"Veselí n. Moravou;Sázava")
    create_projection('12/6/2011',"K.Vary;Tišnov")
    create_projection('12/10/2011',"Dobruška")
    create_projection('12/11/2011',"K.Hora")
    create_projection('12/15/2011',"Opava")
    create_projection('12/16/2011',"K.Hora")
    create_projection('12/19/2011',"Kopřivnice;Nový Jičín")
    create_projection('12/20/2011',"Nový Jičín")
    create_projection('12/21/2011',"Jirkov;Nový Jičín;Bruntál")
    create_projection('12/22/2011',"Bruntál")
    create_projection('12/23/2011',"Bruntál")
    create_projection('12/27/2011',"K.Vary")
    create_projection('12/28/2011',"K.Vary;Červený Kostelec")
    create_projection('1/4/2012',"Chodov")
  end
  
  def create_projection(date,location)
    date = Date.strptime(date, '%m/%d/%Y')
    location.split(';').each do |city|
      Projection.create :date => date, :location => city
    end
  end
end