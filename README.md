# Comando-b-sico-MySQL-
CREATE TABLE clientes (
  id INT PRIMARY KEY AUTO_INCREMENT,
  nome VARCHAR(255) NOT NULL,
  email VARCHAR(255) UNIQUE NOT NULL,
  telefone VARCHAR(20) NOT NULL
);
INSERT INTO clientes (nome, email, telefone) VALUES ('João Silva', 'joao.silva@example.com', '1234567890');
SELECT * FROM clientes WHERE nome LIKE '%Silva%';
