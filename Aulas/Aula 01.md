<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário</title>
    <style>label{display: block; margin-bottom: 10px;}</style>
</head>
<body>
    <form action="" method="get">
        <label>Nome
        <input type="text" name="nome">
        </label>
        <label >E-mail
        <input type="email" name="email">    
        </label>
        <label> Idade
        <input type="number" name="idade" min="1" max="120">
        </label>
        <label>Data de Nascimento
        <input type="date" name="data_nasc">
        </label>
        <label>Senha
        <input type="password" name="Senha">
        </label>
        <label>Arquivos
        <input type="file" name="Arquivo">
        </label>
        <label>Gênero</label>
        <label><input type="radio" name="genero" value="masculino"> Masculino</label>
        <label><input type="radio" name="genero" value="masculino"> Feminino</label>
        <label><input type="radio" name="genero" value="masculino"> Outro</label>
        
        <label>Esportes</label>
        <label><input type="checkbox" name"esporte" value="futebol"> Futebol</label>
        <label><input type="checkbox" name"esporte" value="volei"> Vôlei</label>
        <label><input type="checkbox" name"esporte" value="ciclismo"> Ciclismo</label>
        <label><input type="checkbox" name"esporte" value="natacao"> Natação</label>
    
        <label>UF
            <select name="uf">
                <optgroup label="Centro-oeste">
                    <option value="DF">DF</option>
                    <option value="GO">GO</option>
                    </optgroup>
                <optgroup label="Nordeste">
                    <option value="MA">MA</option>
                    <option value="PI">PI</option>
                    </optgroup> 
                </select>
        </label>
        
        <label>Mensagem
            <textarea name="mensagem" rows="5" cols="30"></textarea>
        </label>
    
        <input type="hidden" name="enviar-dados-oculto">

        <button type="submit">Enviar</button>
    </form>
</body>
</html>
