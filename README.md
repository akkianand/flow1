# Access Control in SomeContract

## Variables

### testStruct

- **Description**: Instance of SomeStruct struct.
- **Access**: Public (`pub`).

### SomeStruct

#### a

- **Description**: Holds a String value.
- **Access**: Public and writable by anyone (`pub(set)`).

#### b

- **Description**: Holds a String value.
- **Access**: Public and writable by anyone (`pub`).

#### c

- **Description**: Holds a String value.
- **Access**: Accessible only within the contract (`access(contract)`).

#### d

- **Description**: Holds a String value.
- **Access**: Accessible only within the struct (`access(self)`).

## Functions

### publicFunc

- **Description**: A public function.
- **Access**: Public (`pub`).

### contractFunc

- **Description**: A function accessible only within the contract.
- **Access**: Accessible only within the contract (`access(contract)`).

### privateFunc

- **Description**: A function accessible only within the struct.
- **Access**: Accessible only within the struct (`access(self)`).
