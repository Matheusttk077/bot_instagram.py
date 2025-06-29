from instagrapi import Client

cl = Client()
cl.login("usuario_teste", "senha_teste")
cl.user_follow("conta_a_seguir")
