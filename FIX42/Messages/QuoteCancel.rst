===============
QuoteCancel (Z)
===============

+---------+----------+
| MsgType | Category |
+=========+==========+
| Z       | APP      |
+---------+----------+

Fields
------

.. list-table::
   :header-rows: 1

   * - Tag

     - Field Name

     - Req'd

     - Data Type

     - Acceptable Enums

   * -

     - *NoQuoteEntries*

     - *

     -

     -

   * - > `231 <http://fixwiki.org/fixwiki/ContractMultiplier>`_

     - ContractMultiplier

     -

     - FLOAT

     -

   * - > `223 <http://fixwiki.org/fixwiki/CouponRate>`_

     - CouponRate

     -

     - FLOAT

     -

   * - > `349 <http://fixwiki.org/fixwiki/EncodedIssuer>`_

     - EncodedIssuer

     -

     - DATA

     -

   * - > `348 <http://fixwiki.org/fixwiki/EncodedIssuerLen>`_

     - EncodedIssuerLen

     -

     - LENGTH

     -

   * - > `351 <http://fixwiki.org/fixwiki/EncodedSecurityDesc>`_

     - EncodedSecurityDesc

     -

     - DATA

     -

   * - > `350 <http://fixwiki.org/fixwiki/EncodedSecurityDescLen>`_

     - EncodedSecurityDescLen

     -

     - LENGTH

     -

   * - > `22 <http://fixwiki.org/fixwiki/IDSource>`_

     - IDSource

     -

     - STRING

     - 1 = CUSIP

   * - >

     -

     -

     -

     - 2 = SEDOL

   * - >

     -

     -

     -

     - 3 = QUIK

   * - >

     -

     -

     -

     - 4 = ISIN_NUMBER

   * - >

     -

     -

     -

     - 5 = RIC_CODE

   * - >

     -

     -

     -

     - 6 = ISO_CURRENCY_CODE

   * - >

     -

     -

     -

     - 7 = ISO_COUNTRY_CODE

   * - >

     -

     -

     -

     - 8 = EXCHANGE_SYMBOL

   * - >

     -

     -

     -

     - 9 = CONSOLIDATED_TAPE_ASSOCIATION

   * - > `106 <http://fixwiki.org/fixwiki/Issuer>`_

     - Issuer

     -

     - STRING

     -

   * - > `205 <http://fixwiki.org/fixwiki/MaturityDay>`_

     - MaturityDay

     -

     - DAYOFMONTH

     -

   * - > `200 <http://fixwiki.org/fixwiki/MaturityMonthYear>`_

     - MaturityMonthYear

     -

     - MONTHYEAR

     -

   * - > `206 <http://fixwiki.org/fixwiki/OptAttribute>`_

     - OptAttribute

     -

     - CHAR

     -

   * - > `201 <http://fixwiki.org/fixwiki/PutOrCall>`_

     - PutOrCall

     -

     - INT

     - 0 = PUT

   * - >

     -

     -

     -

     - 1 = CALL

   * - > `107 <http://fixwiki.org/fixwiki/SecurityDesc>`_

     - SecurityDesc

     -

     - STRING

     -

   * - > `207 <http://fixwiki.org/fixwiki/SecurityExchange>`_

     - SecurityExchange

     -

     - EXCHANGE

     -

   * - > `48 <http://fixwiki.org/fixwiki/SecurityID>`_

     - SecurityID

     -

     - STRING

     -

   * - > `167 <http://fixwiki.org/fixwiki/SecurityType>`_

     - SecurityType

     -

     - STRING

     - ? = WILDCARD_ENTRY

   * - >

     -

     -

     -

     - BA = BANKERS_ACCEPTANCE

   * - >

     -

     -

     -

     - CB = CONVERTIBLE_BOND

   * - >

     -

     -

     -

     - CD = CERTIFICATE_OF_DEPOSIT

   * - >

     -

     -

     -

     - CMO = COLLATERALIZE_MORTGAGE_OBLIGATION

   * - >

     -

     -

     -

     - CORP = CORPORATE_BOND

   * - >

     -

     -

     -

     - CP = COMMERCIAL_PAPER

   * - >

     -

     -

     -

     - CPP = CORPORATE_PRIVATE_PLACEMENT

   * - >

     -

     -

     -

     - CS = COMMON_STOCK

   * - >

     -

     -

     -

     - FHA = FEDERAL_HOUSING_AUTHORITY

   * - >

     -

     -

     -

     - FHL = FEDERAL_HOME_LOAN

   * - >

     -

     -

     -

     - FN = FEDERAL_NATIONAL_MORTGAGE_ASSOCIATION

   * - >

     -

     -

     -

     - FOR = FOREIGN_EXCHANGE_CONTRACT

   * - >

     -

     -

     -

     - FUT = FUTURE

   * - >

     -

     -

     -

     - GN = GOVERNMENT_NATIONAL_MORTGAGE_ASSOCIATION

   * - >

     -

     -

     -

     - GOVT = TREASURIES_PLUS_AGENCY_DEBENTURE

   * - >

     -

     -

     -

     - IET = MORTGAGE_IOETTE

   * - >

     -

     -

     -

     - MF = MUTUAL_FUND

   * - >

     -

     -

     -

     - MIO = MORTGAGE_INTEREST_ONLY

   * - >

     -

     -

     -

     - MPO = MORTGAGE_PRINCIPAL_ONLY

   * - >

     -

     -

     -

     - MPP = MORTGAGE_PRIVATE_PLACEMENT

   * - >

     -

     -

     -

     - MPT = MISCELLANEOUS_PASS_THRU

   * - >

     -

     -

     -

     - MUNI = MUNICIPAL_BOND

   * - >

     -

     -

     -

     - NONE = NO_ISITC_SECURITY_TYPE

   * - >

     -

     -

     -

     - OPT = OPTION

   * - >

     -

     -

     -

     - PS = PREFERRED_STOCK

   * - >

     -

     -

     -

     - RP = REPURCHASE_AGREEMENT

   * - >

     -

     -

     -

     - RVRP = REVERSE_REPURCHASE_AGREEMENT

   * - >

     -

     -

     -

     - SL = STUDENT_LOAN_MARKETING_ASSOCIATION

   * - >

     -

     -

     -

     - TD = TIME_DEPOSIT

   * - >

     -

     -

     -

     - USTB = US_TREASURY_BILL

   * - >

     -

     -

     -

     - WAR = WARRANT

   * - >

     -

     -

     -

     - ZOO = CATS_TIGERS_LIONS

   * - > `202 <http://fixwiki.org/fixwiki/StrikePrice>`_

     - StrikePrice

     -

     - PRICE

     -

   * - > `55 <http://fixwiki.org/fixwiki/Symbol>`_

     - Symbol

     - *

     - STRING

     -

   * - > `65 <http://fixwiki.org/fixwiki/SymbolSfx>`_

     - SymbolSfx

     -

     - STRING

     -

   * - > `311 <http://fixwiki.org/fixwiki/UnderlyingSymbol>`_

     - UnderlyingSymbol

     -

     - STRING

     -

   * - `298 <http://fixwiki.org/fixwiki/QuoteCancelType>`_

     - QuoteCancelType

     - *

     - INT

     - 1 = CANCEL_FOR_SYMBOL

   * -

     -

     -

     -

     - 2 = CANCEL_FOR_SECURITY_TYPE

   * -

     -

     -

     -

     - 3 = CANCEL_FOR_UNDERLYING_SYMBOL

   * -

     -

     -

     -

     - 4 = CANCEL_FOR_ALL_QUOTES

   * - `117 <http://fixwiki.org/fixwiki/QuoteID>`_

     - QuoteID

     - *

     - STRING

     -

   * - `131 <http://fixwiki.org/fixwiki/QuoteReqID>`_

     - QuoteReqID

     -

     - STRING

     -

   * - `301 <http://fixwiki.org/fixwiki/QuoteResponseLevel>`_

     - QuoteResponseLevel

     -

     - INT

     - 0 = NO_ACKNOWLEDGEMENT

   * -

     -

     -

     -

     - 1 = ACKNOWLEDGE_ONLY_NEGATIVE_OR_ERRONEOUS_QUOTES

   * -

     -

     -

     -

     - 2 = ACKNOWLEDGE_EACH_QUOTE_MESSAGES

   * - `336 <http://fixwiki.org/fixwiki/TradingSessionID>`_

     - TradingSessionID

     -

     - STRING

     -

