<!-- Depuis https://gist.github.com/dsample/f847e2cf598fd973240d -->
<div class="progress" style="border: 1px solid #999">
  <div id="progress-bar" style="border-right: ; background-color: #96f; height: 10px; width: 0%"></div>
</div>
<div id="countdown"></div>

<script type="text/javascript">
  function getDaysRemaining(endtime){
    var t = Date.parse(endtime) - Date.parse(new Date());
    var days = Math.floor( t/(1000*60*60*24) );
    return days;
  }
  function getTimeSince(starttime){
    var t = Date.parse(new Date()) - Date.parse(starttime);
    var days = Math.floor( t/(1000*60*60*24) );
    var weeks = Math.floor( days/7 );
    var daysOfWeek = days;
    return {
      'weeks': weeks,
      'days': daysOfWeek
    };
  }

  function humaniseSince(weeks, days) {
    var text = "Déjà " + days;
    text = text.concat(' jours confinés');
    return text;
  }

  function getPercentage(starttime, endtime) {
    startDate = Date.parse(starttime);
    endDate = Date.parse(endtime);

    diff = endDate - startDate;
    totalDays = Math.floor( diff/(1000*60*60*24) );

    var progressDiff = Date.parse(new Date()) - Date.parse(starttime);
    var progressDays = Math.floor( progressDiff/(1000*60*60*24) );

    decimal = progressDays/totalDays;

    percentage = Math.floor(decimal * 100);
    return percentage
  }

  var startDate = '2020-03-17';
  var endDate = '2020-05-11';

  var timeGone = getTimeSince(startDate);
  var daysLeft = getDaysRemaining(endDate);
  var sinceText = humaniseSince(timeGone['weeks'], timeGone['days'])
  var percentComplete = getPercentage(startDate, endDate);

  document.getElementById('progress-bar').style.width = percentComplete.toString() + '%';

  var countdown = document.getElementById('countdown');
  countdown.innerHTML = sinceText + ', ' + daysLeft.toString() + ' jours restants (' + percentComplete + '%)';
</script>
