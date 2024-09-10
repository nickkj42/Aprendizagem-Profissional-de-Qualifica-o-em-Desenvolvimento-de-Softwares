/* Criando projeto final de uma loja PetShop com MySQL */

/* tabelas */
-- 1. Criando banco de dados
create database bd_pet_shop;
-- 2. Acessando Tabela


-- 3. Criando Tabela funcionario
CREATE TABLE `bd_pet_shop`.`tb_func`(
`func_cod` INT NOT NULL PRIMARY KEY,
`func_nome` VARCHAR(40) NOT NULL,
`func_cpf` VARCHAR(20) INT NOT NULL
);



-- 4. Criando Tabela Clientes
CREATE TABLE `bd_pet_shop`.`tb_clientes`(
`cli_cod` INT NOT NULL PRIMARY KEY,
`cli_nome` VARCHAR (40) NOT NULL,
`cli_cpf` VARCHAR(18) NOT NULL,
`cli_end_rua` VARCHAR(40) NULL,
`cli_end_num` VARCHAR (5) NULL,
`cli_end_bairro` VARCHAR(30) NULL,
`cli_end_cep` VARCHAR(9) NULL
);

-- 5. Criando Tabela Compra
CREATE TABLE `bd_pet_shop`.`tb_compra`(
`compra_cod` INT NOT NULL PRIMARY KEY,
`compra_cli_cod` INT NOT NULL,
`compra_func_cod` INT NOT NULL
);

use bd_pet_shop
