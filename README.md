from kivy.app import App
from kivy.uix.label import Label #Classe que contem label
def build():
    return  Label(text='Hello World')
hello_world = App()  #instância de app
hello_world.build = build
hello_world.run()
