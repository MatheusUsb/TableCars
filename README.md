# TableCars
-- Criar a tabela de carros
CREATE TABLE Carros (
    ID INT PRIMARY KEY,
    Marca VARCHAR(50),
    Modelo VARCHAR(50),
    Ano INT,
    Cor VARCHAR(20),
    Preco DECIMAL(10, 2)
);

-- Inserir dados fictícios
INSERT INTO Carros (ID, Marca, Modelo, Ano, Cor, Preco)
VALUES
    (1, 'Toyota', 'Corolla', 2022, 'Prata', 25000.00),
    (2, 'Honda', 'Civic', 2023, 'Azul', 27000.00),
    (3, 'Ford', 'Mustang', 2021, 'Vermelho', 55000.00),
    (4, 'Chevrolet', 'Camaro', 2022, 'Preto', 60000.00),
    (5, 'Volkswagen', 'Golf', 2023, 'Branco', 22000.00);
