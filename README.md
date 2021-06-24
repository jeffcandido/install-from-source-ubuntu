# install-from-source-ubuntu

1 - Baixar o arquivo .tar.gz

2 - Extrair o tarball
sudo tar -xzf app-to-install.tar.gz -C /opt

3 - Verificar se precisa dar permissões de execução/escrita para os arquivos extraídos

4 - Criar um arquivo de extensão *.desktop no caminho /usr/share/applications/ com um conteúdo semelhante a esse:

[Desktop Entry]
Name=IntelliJIDEA
Comment=Integrated Development Environment (IDE) for JVM languages
Exec=/opt/idea-IC-211.7442.40/bin/idea.sh
Icon=/opt/idea-IC-211.7442.40/bin/idea.png
StartupNotify=true
Terminal=false
Type=Application
Categories=API;Development;Programming;IDE;JVM;Kotlin;Java;Gradle

5 - Pronto, seu programa já poderá ser encontrado na pesquisa do Ubuntu.

