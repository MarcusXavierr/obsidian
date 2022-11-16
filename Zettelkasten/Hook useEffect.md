2022-11-10 23:41
Status: #idea
Tags: [[React]] [[Javascript]]

# Hook useEffect

Bom, como o nome já diz, esse hook é muito util quando estamos lidando com efeitos colaterais. Geralmente é usado para lidar com requisições HTTP ou algo do tipo, embora possa ser usado para outros tipos de side effects (como liberar o botão quando todos os campos do input estiverem ok).

O funcionamento desse hook é bem simples, basicamente ele recebe dois parametros.
1. Uma função que será rodada quando alguma dependencia mudar
2. Uma lista de dependencias

então eu tenho algo assim

```typescript
useEffect(() => {
	//func sendo executada
}, [dependencias])
```

Também é bom lembrar que essa func sempre será executada quando a pagina carrega, aí depois fica a cargo da lista de dependencias.

### TL;DR
useEffect te ajuda a lidar com código de deve ser executado em resposta a alguma outra ação

# References

