# Test


##Test Unitarios y de Integración del Backend


 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts
 PASS  src/tests/facility.unit.test.ts (5.543 s)

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts
  ● Console

    console.log
      Executing (default): INSERT INTO `facilities` (`id`,`name`,`description`,`price`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `name`, `description`, `price`, `createdAt`, `updatedAt`, `destroyTime` FROM `facilities` AS `Facility` WHERE (`Facility`.`destroyTime` IS NULL);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `name`, `description`, `price`, `createdAt`, `updatedAt`, `destroyTime` FROM `facilities` AS `Facility` WHERE (`Facility`.`destroyTime` IS NULL AND `Facility`.`id` = 105);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `facilities` SET `name`=?,`description`=?,`price`=?,`updatedAt`=? WHERE (`destroyTime` IS NULL AND `id` = ?)

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Rows updated: 1

      at FacilityRepository.update (src/facility/facility.repository.ts:34:21)

    console.log
      Executing (default): SELECT `id`, `name`, `description`, `price`, `createdAt`, `updatedAt`, `destroyTime` FROM `facilities` AS `Facility` WHERE (`Facility`.`destroyTime` IS NULL AND `Facility`.`id` = 105);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `name`, `description`, `price`, `createdAt`, `updatedAt`, `destroyTime` FROM `facilities` AS `Facility` WHERE (`Facility`.`destroyTime` IS NULL AND `Facility`.`id` = 105);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `facilities` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)


 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 RUNS  src/tests/professional.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
 PASS  src/tests/observation.unit.test.ts (6.128 s)

 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts
  ● Console

    console.log
      Executing (default): INSERT INTO `observations` (`id`,`name`,`professional`,`description`,`medicalHistoryId`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `Observation`.`id`, `Observation`.`name`, `Observation`.`professional`, `Observation`.`description`, `Observation`.`medicalHistoryId`, `Observation`.`createdAt`, `Observation`.`updatedAt`, `professionalData`.`id` AS `professionalData.id`, `professionalData`.`firstname` AS `professionalData.firstname`, `professionalData`.`lastname` AS `professionalData.lastname` FROM `observations` AS `Observation` LEFT OUTER JOIN `professionals` AS `professionalData` ON `Observation`.`professional` = `professionalData`.`id`;

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `Observation`.`id`, `Observation`.`name`, `Observation`.`professional`, `Observation`.`description`, `Observation`.`medicalHistoryId`, `Observation`.`createdAt`, `Observation`.`updatedAt`, `professionalData`.`id` AS `professionalData.id`, `professionalData`.`firstname` AS `professionalData.firstname`, `professionalData`.`lastname` AS `professionalData.lastname` FROM `observations` AS `Observation` LEFT OUTER JOIN `professionals` AS `professionalData` ON `Observation`.`professional` = `professionalData`.`id` WHERE `Observation`.`id` = 70;

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `observations` SET `name`=?,`professional`=?,`description`=?,`medicalHistoryId`=?,`updatedAt`=? WHERE `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Rows updated: 1

      at observationRepository.update (src/observation/observation.repository.ts:48:17)

    console.log
      Executing (default): SELECT `id`, `name`, `professional`, `description`, `medicalHistoryId`, `createdAt`, `updatedAt` FROM `observations` AS `Observation` WHERE `Observation`.`id` = 70;

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `Observation`.`id`, `Observation`.`name`, `Observation`.`professional`, `Observation`.`description`, `Observation`.`medicalHistoryId`, `Observation`.`createdAt`, `Observation`.`updatedAt`, `professionalData`.`id` AS `professionalData.id`, `professionalData`.`firstname` AS `professionalData.firstname`, `professionalData`.`lastname` AS `professionalData.lastname` FROM `observations` AS `Observation` LEFT OUTER JOIN `professionals` AS `professionalData` ON `Observation`.`professional` = `professionalData`.`id` WHERE `Observation`.`id` = 70;

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): DELETE FROM `observations` WHERE `id` = 70

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)


 RUNS  src/tests/integration.test.ts
 RUNS  src/tests/client.unit.test.ts

 RUNS  src/tests/integration.test.ts
 PASS  src/tests/pet.unit.test.ts (6.289 s)

 RUNS  src/tests/integration.test.ts
  ● Console

    console.log
      Executing (default): INSERT INTO `pets` (`id`,`name`,`birthdate`,`type`,`breed`,`weight`,`clientId`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?,?,?);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `Pet`.`id`, `Pet`.`name`, `Pet`.`birthdate`, `Pet`.`type`, `Pet`.`breed`, `Pet`.`weight`, `Pet`.`clientId`, `Pet`.`createdAt`, `Pet`.`updatedAt`, `Pet`.`destroyTime`, `Type`.`id` AS `Type.id`, `Type`.`name` AS `Type.name` FROM `pets` AS `Pet` LEFT OUTER JOIN `types` AS `Type` ON `Pet`.`type` = `Type`.`id` WHERE (`Pet`.`destroyTime` IS NULL);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `Pet`.`id`, `Pet`.`name`, `Pet`.`birthdate`, `Pet`.`type`, `Pet`.`breed`, `Pet`.`weight`, `Pet`.`clientId`, `Pet`.`createdAt`, `Pet`.`updatedAt`, `Pet`.`destroyTime`, `Type`.`id` AS `Type.id`, `Type`.`name` AS `Type.name` FROM `pets` AS `Pet` LEFT OUTER JOIN `types` AS `Type` ON `Pet`.`type` = `Type`.`id` WHERE (`Pet`.`destroyTime` IS NULL AND `Pet`.`id` = 97);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `pets` SET `name`=?,`birthdate`=?,`type`=?,`breed`=?,`weight`=?,`clientId`=?,`updatedAt`=? WHERE (`destroyTime` IS NULL AND `id` = ?)

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Rows updated: 1

      at PetRepository.update (src/pet/pet.repository.ts:46:17)

    console.log
      Executing (default): SELECT `id`, `name`, `birthdate`, `type`, `breed`, `weight`, `clientId`, `createdAt`, `updatedAt`, `destroyTime` FROM `pets` AS `Pet` WHERE (`Pet`.`destroyTime` IS NULL AND `Pet`.`id` = 97);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `Pet`.`id`, `Pet`.`name`, `Pet`.`birthdate`, `Pet`.`type`, `Pet`.`breed`, `Pet`.`weight`, `Pet`.`clientId`, `Pet`.`createdAt`, `Pet`.`updatedAt`, `Pet`.`destroyTime`, `Type`.`id` AS `Type.id`, `Type`.`name` AS `Type.name` FROM `pets` AS `Pet` LEFT OUTER JOIN `types` AS `Type` ON `Pet`.`type` = `Type`.`id` WHERE (`Pet`.`destroyTime` IS NULL AND `Pet`.`id` = 97);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `pets` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)


 RUNS  src/tests/integration.test.ts

 PASS  src/tests/professional.unit.test.ts (6.871 s)

  ● Console

    console.log
      Executing (default): INSERT INTO `professionals` (`id`,`dni`,`firstname`,`lastname`,`address`,`phone`,`email`,`birthDate`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?,?,?,?);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): INSERT INTO `users` (`id`,`username`,`password`,`role`,`professionalId`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?); 

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `professionals` AS `Professional` WHERE (`Professional`.`destroyTime` IS NULL);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `professionals` AS `Professional` WHERE (`Professional`.`destroyTime` IS NULL AND `Professional`.`id` = 84);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `professionals` AS `Professional` WHERE (`Professional`.`destroyTime` IS NULL AND `Professional`.`id` = 84);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `professionals` SET `dni`=?,`lastname`=?,`firstname`=?,`address`=?,`phone`=?,`email`=?,`birthDate`=?,`updatedAt`=? WHERE `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `professionals` AS `Professional` WHERE (`Professional`.`destroyTime` IS NULL AND `Professional`.`id` = 84);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `professionals` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): DELETE FROM `users` WHERE `professionalId` = 84

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)


 PASS  src/tests/client.unit.test.ts (6.899 s)
  ● Console
                                                                                                                                                          
    console.log                                                                                                                                           
      Executing (default): INSERT INTO `clients` (`id`,`dni`,`firstname`,`lastname`,`address`,`phone`,`email`,`birthDate`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?,?,?,?);                                                                                                                              
                                                                                                                                                          
      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)                                                                                  
                                                                                                                                                          
    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `clients` AS `Client` WHERE (`Client`.`destroyTime` IS NULL);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `clients` AS `Client` WHERE (`Client`.`destroyTime` IS NULL AND `Client`.`id` = 94);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `clients` SET `dni`=?,`firstname`=?,`lastname`=?,`address`=?,`phone`=?,`email`=?,`birthDate`=?,`updatedAt`=? WHERE (`destroyTime` IS NULL AND `id` = ?)

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Rows updated: 1

      at ClientRepository.update (src/client/client.repository.ts:41:17)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `clients` AS `Client` WHERE (`Client`.`destroyTime` IS NULL AND `Client`.`id` = 94);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `clients` AS `Client` WHERE (`Client`.`destroyTime` IS NULL AND `Client`.`id` = 94);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `clients` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `pets` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `clientId` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): DELETE FROM `users` WHERE `clientId` = 94

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

 PASS  src/tests/integration.test.ts (11.264 s)
  ● Console

    console.log
      Executing (default): INSERT INTO `clients` (`id`,`dni`,`firstname`,`lastname`,`address`,`phone`,`email`,`birthDate`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?,?,?,?);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Input data: {
        name: 'Test Pet',
        birthdate: '2020-01-01T00:00:00.000Z',
        type: 1,
        breed: 'Test Breed',
        weight: 10,
        clientId: 95
      }

      at add (src/pet/pet.controler.ts:53:11)

    console.log
      Executing (default): INSERT INTO `pets` (`id`,`name`,`birthdate`,`type`,`breed`,`weight`,`clientId`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?,?,?);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): INSERT INTO `professionals` (`id`,`dni`,`firstname`,`lastname`,`address`,`phone`,`email`,`birthDate`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?,?,?,?);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): INSERT INTO `users` (`id`,`username`,`password`,`role`,`professionalId`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?); 

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): INSERT INTO `facilities` (`id`,`name`,`description`,`price`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): INSERT INTO `products` (`id`,`name`,`description`,`price`,`stock`,`category`,`createdAt`,`updatedAt`) VALUES (DEFAULT,?,?,?,?,?,?,?);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `clients` AS `Client` WHERE (`Client`.`destroyTime` IS NULL);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `Pet`.`id`, `Pet`.`name`, `Pet`.`birthdate`, `Pet`.`type`, `Pet`.`breed`, `Pet`.`weight`, `Pet`.`clientId`, `Pet`.`createdAt`, `Pet`.`updatedAt`, `Pet`.`destroyTime`, `Type`.`id` AS `Type.id`, `Type`.`name` AS `Type.name` FROM `pets` AS `Pet` LEFT OUTER JOIN `types` AS `Type` ON `Pet`.`type` = `Type`.`id` WHERE (`Pet`.`destroyTime` IS NULL AND `Pet`.`id` = 98);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `clients` SET `dni`=?,`firstname`=?,`lastname`=?,`address`=?,`phone`=?,`email`=?,`birthDate`=?,`updatedAt`=? WHERE (`destroyTime` IS NULL AND `id` = ?)

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Rows updated: 1

      at ClientRepository.update (src/client/client.repository.ts:41:17)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `clients` AS `Client` WHERE (`Client`.`destroyTime` IS NULL AND `Client`.`id` = 95);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `Pet`.`id`, `Pet`.`name`, `Pet`.`birthdate`, `Pet`.`type`, `Pet`.`breed`, `Pet`.`weight`, `Pet`.`clientId`, `Pet`.`createdAt`, `Pet`.`updatedAt`, `Pet`.`destroyTime`, `Type`.`id` AS `Type.id`, `Type`.`name` AS `Type.name` FROM `pets` AS `Pet` LEFT OUTER JOIN `types` AS `Type` ON `Pet`.`type` = `Type`.`id` WHERE (`Pet`.`destroyTime` IS NULL AND `Pet`.`id` = 98);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `pets` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `Pet`.`id`, `Pet`.`name`, `Pet`.`birthdate`, `Pet`.`type`, `Pet`.`breed`, `Pet`.`weight`, `Pet`.`clientId`, `Pet`.`createdAt`, `Pet`.`updatedAt`, `Pet`.`destroyTime`, `Type`.`id` AS `Type.id`, `Type`.`name` AS `Type.name` FROM `pets` AS `Pet` LEFT OUTER JOIN `types` AS `Type` ON `Pet`.`type` = `Type`.`id` WHERE (`Pet`.`destroyTime` IS NULL AND `Pet`.`id` = 98);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `clients` AS `Client` WHERE (`Client`.`destroyTime` IS NULL AND `Client`.`id` = 95);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `clients` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `pets` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `clientId` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): DELETE FROM `users` WHERE `clientId` = 95

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `dni`, `firstname`, `lastname`, `address`, `phone`, `email`, `birthDate`, `createdAt`, `updatedAt`, `destroyTime` FROM `professionals` AS `Professional` WHERE (`Professional`.`destroyTime` IS NULL AND `Professional`.`id` = 85);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `professionals` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): DELETE FROM `users` WHERE `professionalId` = 85

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `name`, `description`, `price`, `createdAt`, `updatedAt`, `destroyTime` FROM `facilities` AS `Facility` WHERE (`Facility`.`destroyTime` IS NULL AND `Facility`.`id` = 106);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `facilities` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): SELECT `id`, `name`, `description`, `price`, `stock`, `category`, `createdAt`, `updatedAt`, `destroyTime` FROM `products` AS `Product` WHERE (`Product`.`destroyTime` IS NULL AND `Product`.`id` = 56);

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

    console.log
      Executing (default): UPDATE `products` SET `destroyTime`=? WHERE `destroyTime` IS NULL AND `id` = ?

      at Sequelize.log (node_modules/sequelize/src/sequelize.js:1281:15)

A worker process has failed to exit gracefully and has been force exited. This is likely caused by tests leaking due to improper teardown. Try running with --detectOpenHandles to find leaks. Active timers can also cause this, ensure that .unref() was called on them.
                                                                                                                                                          
Test Suites: 6 passed, 6 total                                                                                                                            
Tests:       39 passed, 39 total                                                                                                                          
Snapshots:   0 total                                                                                                                                      
Time:        12.101 s, estimated 15 s                                                                                                                     
Ran all test suites.                                                                                                                                      
 

##Test unitario de Componente en el Frontend


4 specs, 0 failures, randomized with seed  [14444](http://localhost:9876/context.html?seed=14444 "randomized with seed 14444")

 [SignInComponent](http://localhost:9876/context.html?spec=SignInComponent)

-   [should handle error when sign-in fails](http://localhost:9876/context.html?spec=SignInComponent%20should%20handle%20error%20when%20sign-in%20fails)

-   [should show error when passwords do not match](http://localhost:9876/context.html?spec=SignInComponent%20should%20show%20error%20when%20passwords%20do%20not%20match)

-   [should show error when fields are empty](http://localhost:9876/context.html?spec=SignInComponent%20should%20show%20error%20when%20fields%20are%20empty)

-   [should call signInWithClient and navigate on successful sign-up](http://localhost:9876/context.html?spec=SignInComponent%20should%20call%20signInWithClient%20and%20navigate%20on%20successful%20sign-up)

##Test end-to-end en el Frontend

