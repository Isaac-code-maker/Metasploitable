
#### 3. **ssh_access.md**
```markdown
# SSH Access Exploitation

A vulnerabilidade explorada foi identificada no protocolo SSH na porta 22.

- **Comando utilizado**:
  ```bash
  sudo ssh -oHostKeyAlgorithms=+ssh-dss msfadmin@<ip>
  ```

- **Credenciais**: `msfadmin/msfadmin`

Detalhes da vulnerabilidade: 
- O algoritmo de chave `ssh-dss` foi descontinuado, permitindo o uso de um protocolo vulnerável.
