def criar_historia():
    print("Bem-vindo à criação de histórias interativas!\nResponda algumas perguntas para moldar a sua aventura.\n")

    cenario = input("Qual o cenário da história? ")
    personagem = input("Quem é o personagem principal? ")
    objeto_encontrado = input("O que o personagem encontrou? ")
    local_objeto = input("Onde estava esse objeto? ")

    historia = f"\n{personagem} caminhava pelo(a) {cenario} quando, de repente, se deparou com {objeto_encontrado} {local_objeto}. O que acontecerá a seguir? Só o tempo dirá!"

    print(historia)

# Executar a função
criar_historia()
