#### Hae kaikki valuutat tietokannasta
SELECT * FROM currency;

##
#### Hae valuutta lyhenteellä 'EUR'
SELECT * FROM currency WHERE abbreviation = 'EUR';

##
#### Hae valuuttojen lukumäärä tietokannassa
SELECT COUNT(*) AS num_currencies FROM currency;

##
#### Hae valuutta korkeimmalla vaihtokurssilla
SELECT * FROM currency ORDER BY conversion_rate DESC LIMIT 1;