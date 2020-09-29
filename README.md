<div align="center">
  <h1><b>📦 Dogh API</b></h1>
</div>
 
Uma API web para desenvolvedores em desenvolvimento (atualizações constantes).<br/>
Você pode utilizar pacotes como `node-fetch` e `axios` para retornar o response em json.

### 🔍 Retornando informações de 👤 usuários

Você pode utilizar o link abaixo para retornar valores de usuários em json.

``https://botjs.02.fantasy.ovh:10251/api/users`` ou <br/>``https://botjs.02.fantasy.ovh:10251/api/users/`` **+ id** para retornar um usuário específico.

**Retorno**

```js
{
  code: 200,
  users: { ...users }
}
```

### 🔍 Retornando informações de 👾 bots

Você pode utilizar o link abaixo para retornar valores de bots em json.

``https://botjs.02.fantasy.ovh:10251/api/bots`` ou <br/>``https://botjs.02.fantasy.ovh:10251/api/bots/`` **+ id** para retornar um bot específico.

**Retorno**

```js
{
  code: 200,
  bots: { ...bots }
}
```
