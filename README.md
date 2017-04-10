instalar tradução magento2 manual flowecommerce

crie o diretório app/i18n/flowecommerce/pt_br
clone o repo para a pasta  pt_br e copie os arquivos do repo para a pasta pt_br git clone https://github.com/flowecommerce/magento2-pt_br
realize o deploy dos arquivos estáticos para o seu idioma php bin/magento setup:static-content:deploy -lpt_BR
acesse o menu usuário minha conta selecione Português/Brasil em Interface Locale e salve
acesse store -> settings -> general -> options locale -> selecione Português/Brasil e salve
limpe o cache php bin/magento cache:flush 


