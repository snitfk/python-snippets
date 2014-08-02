Datetime
========

Snippets about datetime.


`converting string into datetime`_
----------------------------------

::
    
    from datetime import datetime

    date_object = datetime.strptime('Jun 1 2005  1:33PM', '%b %d %Y %I:%M%p')

    """
    年份差计算
    """
    age = gmtime()[0] - self.birth_date.year
    if gmtime()[1] >= self.birth_date.month:
        age += 1
    return age

.. _converting string into datetime: http://stackoverflow.com/questions/466345/converting-string-into-datetime
