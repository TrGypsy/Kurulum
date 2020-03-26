# Kurulum



#Python3.6 default yapmak ıcın gereklı kod-----

sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.6 8
sudo update-alternatives  --set python /usr/bin/python3.6

---------------------------------

#Gedit Plugins ıcın gereklı kod ------------

sudo apt-get install gedit-plugins

----------------------------------------------

#Vim ve Plug Kurulumu Icın Gereklı Olan Kodlar -------------+
sudo apt-get update
sudo apt-get install vim
sudo apt-get install curl     #Alttakı satırı calıstıra bılmek ıcın curl kurulması gerek
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

sudo apt-get install git    #.Vimrc dekı plugları yuklemek ıcın gıt yuklenmeli

----------------------------


# Traih ve gunu gostermek ıcın kod

gsettings set org.gnome.desktop.interface clock-show-date true
