## Experience

- ##### January 2024 – Present

  ### LSD Game Jam 2024

  #### Game Designer
  
  Worked with my fellow labmates at Pausch Lab to make a game for the LSD Game Jam, where I worked as a Game and Narrative Designer.

  ##### January 2024

  ### Global Game Jam 2024

  #### Game Designer

  Made a game within 48 hours, working as a Game Desginer.

- ##### September 2023 – Present

  ### Next Tech Lab

  #### Pausch Lab Associate
  
  A student led. internationally recognized research lab, honored with the prestigious QS Award.



<style lang="scss">
  @import '../styles/theme.scss';

  :global(.wrapper) > ul {
    position: relative;

    &::before {
      background-color: lighten($background-color, 5%);
      bottom: 0;
      content: ' ';
      left: 20%;
      margin-left: -1px;
      position: absolute;
      top: 0;
      width: 2px;
    }

    > li {
      margin: 0 0 0 20%;
      max-width: 66em;
      padding-left: 2em;
      position: relative;
      width: 80%;

      + li {
        margin-top: 3em;
      }

      > h3 {
        line-height: 1.1;
      }

      > h5 {
        background: darken($heading-color, 2%);
        border-radius: 8px;
        padding: 2px 10px;
        position: absolute;
        right: 104%;
        text-shadow: 0 1px darken($heading-color, 30%);
        white-space: nowrap;
      }

      &::before {
        left: 0;
        margin: 0;
        position: absolute;
        transform: translateX(-50%);
      }
    }

    @media screen and (max-width: 1022px) {
      &::before {
        left: -1.2em;
      }

      > li {
        margin-left: 0;
        max-width: 100%;
        padding-left: 0.5em;
        width: 100%;

        > h5 {
          display: inline-block;
          margin-bottom: 1.2em;
          position: static;
          right: auto;
        }

        &::before {
          transform: translateX(-1.5em);
        }
      }
    }
  }
</style>
